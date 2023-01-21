<script>
	let n = 0;
	const sumar = () => (n += 2);
</script>

<h1>Hello world {n}</h1>
<button on:click={sumar}>Añadir</button>
<a href="/nueva-ruta">Navegar a la ruta nueva</a>

<style>
	h1 {
		margin: 0;
		color: aqua;
	}
</style>
