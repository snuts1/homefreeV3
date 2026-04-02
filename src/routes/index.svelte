<script>
  let count = 0;
</script>

<main>
  <h1>Welcome to HomeFree v3</h1>
  <p>Deployment pipeline test page</p>

  <div class="counter">
    <p>Count: <strong>{count}</strong></p>
    <button on:click={() => count++}>Increment</button>
  </div>
</main>

<style>
  main {
    font-family: sans-serif;
    max-width: 480px;
    margin: 4rem auto;
    text-align: center;
  }

  .counter {
    margin-top: 2rem;
  }

  button {
    padding: 0.5rem 1.5rem;
    font-size: 1rem;
    cursor: pointer;
    border: 2px solid #333;
    border-radius: 4px;
    background: #fff;
  }

  button:hover {
    background: #f0f0f0;
  }
</style>
