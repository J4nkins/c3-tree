<script>
    export let visible;
</script>

{#if visible}
    <div id="loader" style="position: absolute; left: 50%; top: 50%; width: 400px; height: 300px; margin: -150px 0 0 -200px;text-align: center">
        <img src="/loading_bars.svg" alt="loading-bars"/>
    </div>
{/if}
