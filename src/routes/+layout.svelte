<script lang="ts">
	import '../app.scss';
	let { children } = $props();
	const favicon: string = ' ';
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>The office | HAJ</title>
</svelte:head>

{@render children?.()}
