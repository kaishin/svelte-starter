<main>
  <div class="container">
    <h1>Homepage</h1>
    <hr>
    <p>This is my new SvelteKit app.</p>
  </div>
</main>

<script context="module">
  export const hydrate = false;
  export const router = false;
</script>

<style>
  main {
    font-family: sans-serif;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px 20px;
  }

  .container > * {
    width: 100%;
    max-width: 700px;
  }
</style>
