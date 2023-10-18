<main>
	<div class="image" />
	<section>
		<header>
			<h2>PERFUME</h2>
			<h1>Grabrielle Essence Eau De Perfume</h1>
		</header>
		<p>
			A floral, solar and voluptuos interpretation comprosed by Olivier Polge, Perfumer-Creator for
			the house of CHANEL.
		</p>
		<footer>
			<h2>$149.99</h2>
			<p><s>$169.99</s></p>
		</footer>
		<button> Add to Cart</button>
	</section>
</main>

<style>
	:root {
		--text-primary: hsl(228, 12%, 48%);
		--text-secondary: hsl(212, 21%, 14%);
		--accent: hsl(158, 36%, 37%);
		--accent-hover: hsl(157, 46%, 17%);
	}

	main {
		width: 95%;
		height: 90%;
		background-color: hsl(0, 0%, 100%);
		border-radius: 0.5rem;
	}
	div.image {
		border-radius: 0.5rem 0.5rem 0 0;
		height: 250px;
		width: 100%;
		display: block;
		background-image: url('/assets/images/image-product-mobile.jpg');
		background-position: center;
		background-size: cover;
	}

	section {
		padding: 2rem;
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}

	section > p {
		color: var(--text-primary);
	}

	header > h2 {
		font-weight: 500;
		color: var(--text-primary);
		letter-spacing: 0.25rem;
	}

	header > h1 {
		color: var(--text-secondary);
		font-weight: 700;
		font-size: 2rem;
		font-family: Fraunces;
	}

	footer {
		display: flex;
		flex-direction: row;
		align-items: center;
		gap: 2rem;
	}

	footer > h2 {
		color: var(--accent);
		font-weight: 700;
		font-size: 2rem;
		font-family: Fraunces;
	}

	footer > p {
		font-weight: 500;
		color: var(--text-primary);
	}
	button {
		height: 3rem;
		outline: none;
		background-color: var(--accent);
		font-weight: 700;
		font-size: 1rem;
		color: hsl(0, 0%, 100%);
		border-radius: 0.5rem;
	}

	button:hover,
	button:focus {
		background-color: var(--accent-hover);
	}

	@media screen and (min-width: 480px) {
		main {
			height: 90%;
			width: 40%;
			display: flex;
			flex-direction: row;
		}

		header > h1 {
			font-size: 2.5rem;
		}
		section > p {
			font-size: 1.25rem;
		}

		div.image {
			height: 550px;
			width: 50%;
			background-image: url('/assets/images/image-product-desktop.jpg');

			border-radius: 0.5rem 0 0 0.5rem;
		}
		section {
			width: 50%;
			display: flex;
			flex-direction: column;
			gap: 3rem;
		}
	}
</style>
