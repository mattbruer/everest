<script>
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import Navbar from '../components/Navbar.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="fixed top-0 left-0 z-50 w-full">
	<Navbar />
</div>
<div class="pt-16">
	{@render children()}
</div>
