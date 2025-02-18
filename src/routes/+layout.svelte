<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<nav>
	<a href="/">home</a>
	<a href="/contact">contact</a>
</nav>

{@render children()}
