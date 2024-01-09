<script>
    import Nav from '$lib/nav.svelte';
</script>


<h1>Svelte's space</h1>
<Nav />

<slot></slot>

<style lang="scss">
   :global(body) {
   width: 400px;
   margin: 0 auto;
   font-family: sans-serif;
 }
</style>