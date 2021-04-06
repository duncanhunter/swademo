<script>
	import Tag from '$lib/Tag.svelte';
	export let title;
	export let publishedDate;
	export let tags;
	export let meta;
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="Description" content="{meta}">
</svelte:head>

<div class="font-sans mb-10">
	<h1 class="break-normal text-white">
		{title}
	</h1>
	<p class="text-sm md:text-base text-gray-300">
		Published {publishedDate}
	</p>
	<p class="text-sm font-normal text-gray-300">
		Tags: {#each tags as tag}
			<Tag {tag} />
		{/each}
	</p>
</div>
