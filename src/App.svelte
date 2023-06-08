<script>
	import Card from './components/Card.svelte';
</script>
<nav>
	<a href="#home">Home</a>
	<a href="#about">About</a>
	<a href="#exhibitions">Exhibitions</a>
	<a href="#contact">Contact</a>
</nav>
<main>
	<Card></Card>
</main>
	

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	nav{
		background-color: darkblue;
		width: 100%;
	}
	
	nav a{
		display: inline-block;
		padding: 8px 16px;
		color:rgba(216, 218, 205, 1);
		text-decoration: none;
	}
	
	nav a:hover{
		background-color: lightskyblue;
		
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>