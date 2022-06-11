<script>
  import Theme from "$lib/Theme.svelte";
</script>

<Theme>
  <div id="layout-container">
    <slot />
  </div>
</Theme>

<style>
  :global(body) {
    margin: 0;
  }

  #layout-container {
    height: 100vh;
    background-color: var(--secondary-colour);
  }
</style>
