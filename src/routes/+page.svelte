<script lang="ts">
	const email = 'ceo@joesolo.com';
</script>

<svelte:head>
	<title>JoeSolo — Solo Strategy for Independent Professionals</title>
	<meta name="description" content="JoeSolo helps independent professionals build sustainable solo businesses." />
</svelte:head>

<main class="min-h-screen bg-white text-gray-900">
	<!-- Hero -->
	<section class="flex flex-col items-center justify-center min-h-screen px-6 text-center">
		<h1 class="text-5xl font-bold tracking-tight mb-4">JoeSolo</h1>
		<p class="text-xl text-gray-500 max-w-xl mb-8">
			Strategy and tools for independent professionals who work alone — and win alone.
		</p>
		<a
			href="mailto:{email}"
			class="inline-block bg-black text-white px-8 py-3 rounded-full text-sm font-medium hover:bg-gray-800 transition-colors"
		>
			Get in touch
		</a>
	</section>
</main>
