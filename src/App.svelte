<script lang="ts">
  export let name: string;
</script>

<main class="flex flex-col items-center">
  <h1 class="text-5xl uppercase font-light py-8 px-4 text-orange-600">
    Hello {name}!
  </h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial" class="underline">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
</main>
