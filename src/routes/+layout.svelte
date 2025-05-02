<script>
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}

<style>
	:global(*) {
		padding: 0;
		margin: 0;
		box-sizing: border-box;
	}

	:global(body) {
		background-color: var(--color-background);
		color: var(--color-text);
		font-family:
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			Roboto,
			Oxygen,
			Ubuntu,
			Cantarell,
			'Open Sans',
			'Helvetica Neue',
			sans-serif;
	}
	:global(a) {
		color: inherit;
		text-decoration: none;
	}
	:global(a:hover) {
		color: var(--color-background);
		background: var(--color-ochre);
	}
</style>
