<section>
	<div class="overlay" />
	<h1 class="animate">
		<span>Welcome </span>
		<span>to My Home!</span>
	</h1>
</section>

<style>
	section {
		height: 95vh;
		background: no-repeat 31% / cover url('../assets/barnum.jpg');
		display: flex;
		justify-content: center;
		position: relative;
	}

	h1 {
		z-index: 1;
		color: rgb(255 217 217);
		font-size: 3rem;
		font-weight: bolder;
		margin-top: 40%;
	}

	h1 span {
		text-align: left;
		width: 100%;
		display: block;
	}

	.overlay {
		position: absolute;
		top: 0;
		background-color: rgba(240, 117, 179, 0.317);
		width: 100%;
		height: 100%;
		backdrop-filter: blur(4 px);
		background: rgb(2, 0, 36);
		background: linear-gradient(
			rgba(2, 0, 36, 1) 0%,
			rgba(212, 72, 181, 0.3) 29%,
			rgba(0, 209, 255, 0.3) 71%
		);

		/* background: linear-gradient(
			180deg,
			rgba(2, 0, 36, 1) 0%,
			rgba(0, 209, 255, 0.3) 19%,
			rgba(212, 72, 181, 0.3) 100%
		); */
	}

	.animate {
		background-image: linear-gradient(-225deg, #231557 0%, #44107a 29%, #ff1361 67%, #fff800 100%);
		background-size: auto auto;
		background-clip: border-box;
		background-size: 00% auto;
		color: #fff;
		background-clip: text;
		text-fill-color: transparent;
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		animation: textclip 4s linear infinite;
		display: inline-block;
		font-size: 190px;
	}

	@keyframes textclip {
		to {
			background-position: 200% center;
		}
	}
</style>
