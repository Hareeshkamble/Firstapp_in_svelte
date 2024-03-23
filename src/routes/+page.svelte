<script>

</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="h-screen">
	<div class="background absolute ">
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
		<span></span>
	 </div>
<div class=" w-full h-[80vh] flex items-center justify-center">
	
	<div>
		<p class="text-tertiary text-[20px]">Hi Its Me </p>
		<h1 class="hero font-bold">Hareesh</h1>
	</div>
</div>

</section>
<style>
	 .hero{
    font-size: 72px;
    /* background: -webkit-linear-gradient( right,#eee, #333); */
    background: url("https://img.freepik.com/free-vector/gradient-trendy-background_23-2150417179.jpg");
    -webkit-background-clip: text;
    background-position: top;
    -webkit-text-fill-color: transparent;
}
@keyframes move {
    100% {
        transform: translate3d(0, 0, 1px) rotate(360deg);
    }
}

.background {
	z-index: 1;
    position: fixed;
    width: 100vw;
    height: 100vh;
    top: 0;
    left: 0;
    background: transparent;
    overflow: hidden;
}

.background span {
    width: 13vmin;
    height: 13vmin;
    border-radius: 13vmin;
    backface-visibility: hidden;
    position: absolute;
    animation: move;
    animation-duration: 45;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}


.background span:nth-child(0) {
    color: #583C87;
    top: 97%;
    left: 89%;
    animation-duration: 6s;
    animation-delay: -39s;
    transform-origin: 4vw -8vh;
    box-shadow: 26vmin 0 3.515276805616259vmin currentColor;
}
.background span:nth-child(1) {
    color: #583C87;
    top: 100%;
    left: 31%;
    animation-duration: 14s;
    animation-delay: -21s;
    transform-origin: 9vw -17vh;
    box-shadow: -26vmin 0 3.998150017426428vmin currentColor;
}
.background span:nth-child(2) {
    color: #E45A84;
    top: 44%;
    left: 75%;
    animation-duration: 19s;
    animation-delay: -41s;
    transform-origin: 20vw 3vh;
    box-shadow: 26vmin 0 3.602204702685571vmin currentColor;
}
.background span:nth-child(3) {
    color: #583C87;
    top: 14%;
    left: 100%;
    animation-duration: 32s;
    animation-delay: -1s;
    transform-origin: -24vw -23vh;
    box-shadow: 26vmin 0 3.3008935170962923vmin currentColor;
}
.background span:nth-child(4) {
    color: #f9d3e0;
    top: 63%;
    left: 29%;
    animation-duration: 24s;
    animation-delay: -11s;
    transform-origin: 4vw -8vh;
    box-shadow: 26vmin 0 4.150746578653045vmin currentColor;
}
.background span:nth-child(5) {
    color: #E45A84;
    top: 44%;
    left: 44%;
    animation-duration: 16s;
    animation-delay: -18s;
    transform-origin: -22vw 14vh;
    box-shadow: 26vmin 0 4.172924867601992vmin currentColor;
}
.background span:nth-child(6) {
    color: #583C87;
    top: 63%;
    left: 24%;
    animation-duration: 50s;
    animation-delay: -48s;
    transform-origin: -16vw -15vh;
    box-shadow: 26vmin 0 3.5767280866126177vmin currentColor;
}
.background span:nth-child(7) {
    color: #E45A84;
    top: 45%;
    left: 40%;
    animation-duration: 11s;
    animation-delay: -3s;
    transform-origin: 14vw 14vh;
    box-shadow: -26vmin 0 3.4768290605115073vmin currentColor;
}
.background span:nth-child(8) {
    color: #f9d3e0;
    top: 80%;
    left: 51%;
    animation-duration: 22s;
    animation-delay: -25s;
    transform-origin: -19vw 16vh;
    box-shadow: -26vmin 0 3.348594216857268vmin currentColor;
}

</style>


