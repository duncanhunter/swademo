<script context="module" lang="ts">
	// export const ssr = false;
	import Counter from '$lib/Counter.svelte';
	// import Example from '$lib/Example.svx';
</script>

<main>
	<h1>Hello world!</h1>

	<Counter />
	<!-- <Example/> -->

	<p>Visit <a class="text-blue-600 underline" href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte apps.</p>
	<p>
		Visit <a href="example-markdown">the /example-markdown page</a> to see some markdown rendered by
		mdsvex.
	</p>
</main>

<style style lang="postcss">
	main {
		@apply text-center;
		@apply p-4;
		@apply mx-auto;
	}

	h1 {
		@apply text-red-600;
		@apply uppercase;
		@apply text-6xl;
		@apply font-thin;
		@apply leading-tight;
		@apply my-16 mx-auto;
		@apply max-w-xs;
	}

	p {
		@apply max-w-xs;
		@apply my-8 mx-auto;
		@apply leading-snug;
	}

	@screen sm {
		h1 {
			@apply max-w-none;
		}

		p {
			@apply max-w-none;
		}
	}
</style>
