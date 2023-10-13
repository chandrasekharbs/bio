<script>
	import '../app.postcss';
	import Footer from './components/footer.svelte';
	import Header from './components/header.svelte';
</script>
<svelte:head>
    <title>Profile | Chandra Sekhar</title> 
	<link rel="icon" href="/profile.png" />
</svelte:head>
<div class="container mx-auto">
	<Header />
	<slot />
	<Footer />
</div>
