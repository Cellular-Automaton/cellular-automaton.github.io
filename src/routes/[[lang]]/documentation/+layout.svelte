<script>
  import Sidebar from '$lib/Sidebar.svelte';

  let props = $props();
</script>

<Sidebar />
{@render props.children()}
