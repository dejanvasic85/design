<script>
	import '../reset.css';
	import '../style.css';
</script>

<header>
	<h1 class="fake-logo">Fake logo</h1>
	<nav>
		<a href="#">Home</a>
		<a href="#">About</a>
		<a href="#">Contact</a>
	</nav>
</header>

<main class="layout">
	<slot />
</main>

<footer>
	<nav>
		<a href="#">Home</a>
		<a href="#">About</a>
		<a href="#">Contact</a>
	</nav>
</footer>
