<script lang="ts">
    import Calculator from '../lib/Calculator.svelte';
</script>

<svelte:head>
    <title>Simple Calculator</title>
    <meta name="description" content="A modern Ocean Professional-themed simple calculator built with Svelte." />
</svelte:head>

<div class="page">
    <Calculator />
</div>

<style>
    .page {
        display: flex;
        align-items: center;
        justify-content: center;
        min-height: 60vh;
        width: 100%;
        padding: 1rem;
    }
</style>
