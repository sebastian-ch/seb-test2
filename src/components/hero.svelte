<script>
	import robo from '../assets/feb1.svg';
</script>

<div class="max-w-screen-xl mx-auto px-5">
	<main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-12 md:pb-24 ">
		<div>
			<h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight xl:tracking-tighter">
				Web Design and Development
			</h1>
			<p class="text-lg mt-4 text-slate-600 max-w-xl">
				Custom websites, like this one (works on mobile too!)
			</p>
		</div>
		<div class="py-6 md:order-1 hidden md:block">
			<img src={robo} alt="robot" width="250px" />
		</div>
	</main>
</div>

<style>
	img:hover {
		-webkit-transform: scaleX(-1);
		transform: scaleX(-1);
	}
</style>
