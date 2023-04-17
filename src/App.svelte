<script>
	import Navbar from './components/Navbar.svelte';
	import Tarea from './components/Tarea.svelte';
</script>

<main class="fondo">
	<Navbar />
	<Tarea />
</main>

<style>
	.fondo {
		background-image: url(../assets/img/fondo.png);
		height: 100vh;
		background-position: center;
		background-size: cover;
	}
</style>