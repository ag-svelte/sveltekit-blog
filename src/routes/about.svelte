<script lang="ts">
	import Meta from '$lib/components/Meta.svelte';
</script>

<Meta title="About" />

<h1>About</h1>
<p>You can always find and contact me in the below places:</p>
<ul class="placesList">
	<li>
		<a
			target="_blank"
			rel="external"
			href="https://github.com/pawelblaszczyk5/"
			class="link placesList__link">Github</a
		>
	</li>
	<li>
		<a
			target="_blank"
			rel="external"
			href="https://www.linkedin.com/in/pawel-blaszczyk/"
			class="link placesList__link">LinkedIn</a
		>
	</li>
	<li>
		<a target="_blank" rel="external" href="mailto:pawelblaszczyk@wir.pl" class="link">Email</a>
	</li>
</ul>
<p>
	The logo of this site has been made by my amazing girlfriend - you can find more of her works <a
		target="_blank"
		href="https://www.instagram.com/ada_guzik/"
		rel="external"
		class="link">here</a
	>.
</p>

<style>
	.placesList {
		list-style-position: inside;
		margin-bottom: 1rem;
	}

	.placesList__link {
		margin: 0.5rem 0;
		display: inline-block;
	}
</style>
