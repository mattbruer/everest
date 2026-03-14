<script>
	import { page } from '$app/stores';
</script>

<div class="flex h-12 items-center justify-around bg-white shadow">
	<a href="/" class={$page.url.pathname === '/' ? 'underline' : ''}>Home</a>
	<a href="/services" class={$page.url.pathname === '/services' ? 'underline' : ''}>Services</a>
	<a
		href="/meet-the-provider"
		class={$page.url.pathname === '/meet-the-provider' ? 'underline' : ''}>Who Is Ann?</a
	>
</div>

<style>
</style>
