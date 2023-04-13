<script>
  import Sparticles from "sparticles";
  let options = { color: "gold", shape: "star", speed: 50 };
  function addSparticles(node) {
    new Sparticles(node, options);
  }
</script>

<main use:addSparticles>
  <h1>Sparticles in Svelte</h1>
  <p>Visit <a href="https://svelte.dev">svelte.dev</a> to read the documentation</p>
</main>

<style>
  main {
    height: 100%;
  }
</style>
