<script context="module">
    import { browser } from '$app/env';
    export const hydrate = true;
    export const router = browser;
    export const prerender = true;
</script>

<script>
    import '$lib/global.scss';
</script>

<svelte:head>
    <title>Chronos</title>
</svelte:head>

<slot />
