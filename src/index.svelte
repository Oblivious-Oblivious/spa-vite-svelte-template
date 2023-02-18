<script>
    import svelte_logo from "./assets/svelte_logo.svg";
    import vite_logo from "/vite_logo.svg";
    
    import Counter from "./lib/Counter.svelte";
</script>

<main>
    <div>
        <a href="https://vitejs.dev" target="_blank" rel="noreferrer"> 
            <img src={vite_logo} class="logo" alt="Vite Logo"/>
        </a>
        <a href="https://svelte.dev" target="_blank" rel="noreferrer"> 
            <img src={svelte_logo} class="logo svelte" alt="Svelte Logo"/>
        </a>
    </div>
    
    <h1>Vite + Svelte</h1>
    
    <div class="card">
        <Counter/>
    </div>
    
    <p class="read-the-docs">
        Click on the Vite and Svelte logos to learn more test2
    </p>
</main>

<style lang="scss">
    .logo {
        height: 6em;
        padding: 1.5em;
        will-change: filter;
        transition: filter 300ms;

        &:hover {
            filter: drop-shadow(0 0 2em #646cffaa);
        }

        &.svelte:hover {
            filter: drop-shadow(0 0 2em #ff3e00aa);
        }
    }
    
    h1 {
        font-size: 3.2em;
    }

    .card {
        padding: 2em;
    }
    
    .read-the-docs {
        color: #888;
    }
</style>
