<script lang="ts">
	import '../scss/_app.scss';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
	<link
		href="https://fonts.googleapis.com/css2?family=Spline+Sans:wght@300;400;500;600;700&display=swap"
		rel="stylesheet"
	/>
	<link
		rel="stylesheet"
		href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@20,200,1,0"
	/>
	<style>
		.material-symbols-rounded {
			font-size: 20px;
			font-variation-settings: 'FILL' 1, 'wght' 200, 'GRAD' 0, 'opsz' 16;
		}
	</style>
</svelte:head>

<main>
	<slot />
</main>
