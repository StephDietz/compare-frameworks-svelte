<script>
	let count = 0;

	function increment() {
		count += 1
	};
</script>

<main>
	<div class="container">
		<img src="JavaScript-logo.png" alt="">
		<h1>Comparing JS Frameworks: This one is Svelte</h1>
		<div class="count">{ count }</div>
		<button on:click={increment}>Increment</button>
	</div>
</main>

<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 15px;
	}
	img {
		width: 20%;
	}
	h1 {
		font-size: 25px;
		font-weight: bold;
		margin-top: 15px;
		text-align: center;
	}
	.count {
		font-size: 45px;
		font-weight: bold;
		color: green;
		margin-top: 15px;
		margin-bottom: 15px;
	}

</style>
