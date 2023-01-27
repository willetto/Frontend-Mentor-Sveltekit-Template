<script>
</script>

<main>
	<slot />
</main>
<footer class="attribution">
	Challenge by
	<a href="https://www.frontendmentor.io?ref=challenge" target="_blank"> Frontend Mentor</a>. Coded
	by
	<a href="https://www.yourname.com" target="_blank">Your Name</a>.
</footer>

<style lang="scss" global>
	@import '/src/lib/styles/stylereset.css';

	@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap');

	main {
		display: grid;
		place-items: center;
		margin-top: 70px;
	}
	.attribution {
		font-size: 11px;
		text-align: center;
		margin-top: 3rem;
	}
	.attribution a {
		color: hsl(228, 45%, 44%);
	}
</style>
