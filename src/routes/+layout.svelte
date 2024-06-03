<svelte:head>
	<title>Svelte 5 Todo App</title>
</svelte:head>

<main>
	<slot />
</main>

<style>
	:global(html, body) {
		height: 100%;
	}

	:global(body) {
		display: grid;
		place-content: center;
		background-color: #fff;
	}
</style>