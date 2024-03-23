<script>
	import Header from './Header.svelte';
	import './styles.css';
	import Hero from "./about/+page.svelte"

</script>

<div class="app bg-secondary w-full">
	<Header />

	<main>
    <slot/>
	</main>

	<footer>
		<p>
			copyrights by Hareesh
		</p>
	</footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		flex-wrap:wrap;

	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		box-sizing: border-box;
		flex-wrap:wrap;

	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;

		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}


</style>
