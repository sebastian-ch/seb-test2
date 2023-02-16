<script>
	import Pagecontainer from '../components/pagecontainer.svelte';
	import Navbar from '../components/navbar.svelte';
	import Footer from '../components/footer.svelte';
	import '../app.css';
</script>

<Pagecontainer>
	<Navbar />

	<slot />

	<Footer />
</Pagecontainer>
