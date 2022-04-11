<script>
	import '$lib/globalStyles.css';
</script>

<svelte:head>
	<title>Frontend Mentor : QR Code</title>
</svelte:head>

<main>
	<section>
		<div class="image"><img src="/image-qr-code.png" alt="qr code" /></div>
		<h1>Improve your front-end skills by building projects</h1>
		<p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
	</section>
</main>

<style>
	main {
		background-color: var(--gray);
		height: 100vh;
		display: grid;
		place-content: center;
	}

	section {
		background-color: var(--white);
		box-shadow: 0rem 1.5625rem 1.5625rem rgba(0, 0, 0, 0.0476518);
		border-radius: 1.25rem;
		width: 20rem;
		overflow: hidden;
		padding: 1rem;
	}

	img {
		border-radius: 0.625rem;
		margin-bottom: 1.5rem;
	}

	h1 {
		font-weight: 700;
		font-size: 1.375rem;
		line-height: 1.75rem;
		text-align: center;
		color: var(--darkBlue);
		margin-bottom: 1rem;
	}
	p {
		margin: 0 auto;
		width: 16rem;
		font-style: normal;
		font-weight: 400;
		font-size: 0.9375rem;
		line-height: 1.1875rem;
		text-align: center;
		letter-spacing: 0.0117rem;
		color: var(--grayishblue);
		margin-bottom: 1.3125rem;
	}
</style>
