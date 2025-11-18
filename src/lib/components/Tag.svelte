<script lang="ts">
    let { children } = $props();
</script>

<span
    class="dark:bg-brown-800 font-semibold bg-brown-200 py-1 px-2 text-sm rounded-full"
    >{@render children()}</span
>
