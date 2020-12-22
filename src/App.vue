<template>
	<div id="app" class="bg-gray-200">
		<header class="bg-gray-900 flex justify-between items-center content-center px-4 py-3">
			<div>
				<img src="./assets/logo.svg" class="h-8 w-auto" />
			</div>
			<div class="flex content-center">
				<button>
					<svg
						class="h-6 w-6 fill-current text-gray-500"
						version="1.1"
						xmlns="http://www.w3.org/2000/svg"
						xmlns:xlink="http://www.w3.org/1999/xlink"
						x="0px"
						y="0px"
						width="24px"
						height="24px"
						viewBox="0 0 24 24"
						style="enable-background:new 0 0 24 24;"
						xml:space="preserve"
					>
						<g id="Icons" style="opacity:0.75;">
							<path
								id="menu"
								d="M6,15h12c0.553,0,1,0.447,1,1v1c0,0.553-0.447,1-1,1H6c-0.553,0-1-0.447-1-1v-1C5,15.447,5.447,15,6,15z M5,11v1
		c0,0.553,0.447,1,1,1h12c0.553,0,1-0.447,1-1v-1c0-0.553-0.447-1-1-1H6C5.447,10,5,10.447,5,11z M5,6v1c0,0.553,0.447,1,1,1h12
		c0.553,0,1-0.447,1-1V6c0-0.553-0.447-1-1-1H6C5.447,5,5,5.447,5,6z"
							/>
						</g>
					</svg>
				</button>
			</div>
		</header>
		<section class="flex justify-between bg-gray-800 px-4 py-3">
			<div class="relative">
				<div class="absolute inset-y-0 left-0">
					<svg xmlns="http://www.w3.org/2000/svg" width="12" height="13">
						<g stroke-width="2" stroke="#6c6c6c" fill="none">
							<path d="M11.29 11.71l-4-4" />
							<circle cx="5" cy="5" r="4" />
						</g>
					</svg>
				</div>

				<input class="bg-gray-900 text-white rounded px-4 py-3" placeholder="Search by keywords" />
				<button>Filters</button>
			</div>
		</section>
		<main>
			<h3>Los Angeles</h3>
			<p>Live like the stars in these luxurious Southern California estates.</p>
		</main>
	</div>
</template>

<script>
export default {
	name: "App",
	components: {},
};
</script>

<style src="./assets/css/tailwind.css"></style>
