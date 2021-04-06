<script>
	export let tag;
</script>

<a href={tag.link} target="_blank" rel="noopener">
	<span
		class="inline-flex items-center px-3 py-0.5 rounded-full text-sm font-medium leading-5 text-blue-400 border-2 border-blue-400 mx-1 my-1 hover:bg-blue-400 hover:text-black"
	>
		{tag.name}
	</span>
</a>
