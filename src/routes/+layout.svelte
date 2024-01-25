<script>
	import Footer from '$lib/components/layout/Footer.svelte';
	import Header from '$lib/components/layout/Header.svelte';
	import Lenis from '$lib/components/shared/Lenis.svelte';
	import ViewTransition from '$lib/components/shared/ViewTransition.svelte';
	import '$lib/styles/app.css';
</script>

<Lenis />
<ViewTransition />
<Header />
<main class="container mx-auto p-4 min-h-screen">
	<slot />
</main>
<Footer />
