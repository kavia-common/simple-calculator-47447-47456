<script lang="ts">
    import '../app.css';
    let { children } = $props();
</script>

<main>
    {@render children()}
</main>

<style>
    main {
        display: flex;
        min-height: 100vh;
        width: 100%;
        align-items: center;
        justify-content: center;
        background: radial-gradient(1200px 600px at 50% -10%, rgba(37,99,235,0.15), rgba(249,250,251,0) 70%),
                    linear-gradient(180deg, rgba(59,130,246,0.05), rgba(249,250,251,1));
    }
</style>
