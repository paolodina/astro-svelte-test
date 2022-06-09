<script>
    export let count = 0;

    const handleClick = (e) => {
        count += 1;
    };
</script>

<h1>Svelte</h1>
<button
    style="padding: 20px 40px; background: blue; color: white"
    on:click={handleClick}>{count}</button
>
