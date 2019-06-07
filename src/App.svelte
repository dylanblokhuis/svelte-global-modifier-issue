<script>
	export let name;
</script>

<style>
	:global(h1) {
		color: purple;
	}
</style>

<svelte:options tag="my-component" />

<h1>Hello {name}!</h1>
