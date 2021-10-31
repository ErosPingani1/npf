<script>
	import Router from 'svelte-spa-router';
	import Index from './routes/Index.svelte'
</script>

<Router routes={{
	'/': Index
}} />

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>