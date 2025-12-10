<script>
	import favicon from '$lib/assets/favicon.svg';
	
	//fonts
	import '@fontsource/alfa-slab-one';
	// Supports weights 400-800
	import '@fontsource-variable/baloo-2';
	import '@fontsource/calistoga';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
