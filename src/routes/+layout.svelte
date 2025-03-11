<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<nav class="bg-gray-800 p-4 text-white">
	<div class="flex items-center justify-between">
		<div>
			<a href="/">Logo</a>
		</div>
		<div class="flex gap-3">
			<a href="/#Services">Services</a>
			<a href="/about">About</a>
			<a href="/#Specialties">Specialties</a>
			<a href="/#Reviews">Reviews</a>
			<a href="/contact">Contact</a>
		</div>
	</div>
</nav>

{@render children()}
