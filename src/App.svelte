<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <a href="http://effici.xyz" target="_blank" rel="noreferrer"> 
      <img src="https://effici.xyz/wp-content/uploads/2023/01/index.jpg" class="logo" alt="Vite Logo" />
    </a>
  </div>
  <h1>Zea's Test Project</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    This is a default template in Stackblitz, a web based vscode. It was built with Vite and Svelte.
  </p>

</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>