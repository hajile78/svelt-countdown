<script>
	import Header from '../lib/header.svelte';
	import '../app.css';
</script>

<Header />

<div class="container">
	<div class="main">
		<slot />
	</div>
	<aside class="linkQuote">
		<div class="links" />
		<div class="quote" />
	</aside>
</div>

<footer class="footer">Copyright © Wintertons.us 2020</footer>
