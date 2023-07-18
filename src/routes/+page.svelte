<script>
</script>

<svelte:head>
	<title>Golfying - golf course sniper</title>
	<meta
		name="description"
		content="Svelte demo app"
	/>
</svelte:head>

<section
	class="flex grow w-100 flex-col flex-wrap h-100 space-y-28 h-full items-center justify-center"
>
	<p class="text-white text-7xl font-light">
		What are <span class="text-blue-600">you</span> looking for?
	</p>
	<div class="flex space-x-3">
		<button
			class="py-3 shadow rounded bg-blue-600 font-bold border-0 uppercase px-5 text-gray-300 hover:bg-blue-700 hover:shadow-lg hover:text-gray-300 active:text-gray-400 active:shadow-sm active:bg-blue-700 transition"
		>
			Clubs and courses for beginners
		</button>

		<button
			class="py-3 shadow rounded border-2 border-blue-600 text-blue-600 font-bold uppercase px-5 hover:bg-blue-600 hover:shadow-lg hover:text-gray-300 active:text-gray-400 active:shadow-sm active:bg-blue-700 transition"
		>
			Most popular courses in your area
		</button>
	</div>
</section>
