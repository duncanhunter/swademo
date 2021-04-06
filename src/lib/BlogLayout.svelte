<script lang="ts">
	import { onMount } from 'svelte'
	export let layout;
	export let title;
	export let meta;
	export let slug;
	export let outline;
	export let tags;
	export let publishedDate;
	/**
	 *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
	 *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
	/*
	 */
	onMount(() => {
		// const disqus_config = function () {
		// 	this.page.url = 'PAGE_URL' // Replace PAGE_URL with your page's canonical URL variable
		// 	this.page.identifier = 'PAGE_IDENTIFIER' // Replace PAGE_IDENTIFIER with your page's unique identifier variable
		// 	this.page.title = 'foo'
		// }
		// ;(function () {
		// 	// DON'T EDIT BELOW THIS LINE
		// 	var d = document,
		// 		s = d.createElement('script')
		// 	s.src = 'https://duncanduncanhuntercomau.disqus.com/embed.js'
		// 	s.setAttribute('data-timestamp', +new Date())
		// 	;(d.head || d.body).appendChild(s)
		// })()
	})
</script>

<!-- <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript> -->
<!-- Copy
    (Recommended) Edit the RECOMMENDED CONFIGURATION VARIABLES section using your CMS or platform's dynamic values. See our documentation to learn why defining identifier and url is important for preventing duplicate threads.
    How to display comment count
    
    Place the following code before your site's closing </body> tag: -->
<!-- Copy
        Append #disqus_thread to the href attribute in your links. This will tell Disqus which links to look up and return the comment count. For example: <a href="http://foo.com/bar.html#disqus_thread">Link</a>.
        Additional customization
        See our Adding comment count links to your home page documentation.
        BackConfigure
        Having trouble with installation?
        
        Contact Support
        FeaturesCompanyLogosHelpBlogAPIJobsTerms & Policies© 2021 · Disqus -->

<div>
	<div class="relative py-16 bg-primary text-white overflow-hidden">
		<div class="hidden lg:block lg:absolute lg:inset-y-0 lg:h-full lg:w-full">
			<!-- <div class="relative h-full text-lg max-w-prose mx-auto" aria-hidden="true"> -->
			<div class="relative h-full text-lg max-w-prose mx-auto">
				<svg
					class="absolute top-12 left-full transform translate-x-32"
					width="404"
					height="384"
					fill="none"
					viewBox="0 0 404 384"
				>
					<defs>
						<pattern
							id="74b3fd99-0a6f-4271-bef2-e80eeafdf357"
							x="0"
							y="0"
							width="20"
							height="20"
							patternUnits="userSpaceOnUse"
						>
							<rect x="0" y="0" width="4" height="4" class="text-tertiary" fill="currentColor" />
						</pattern>
					</defs>
					<rect width="404" height="384" fill="url(#74b3fd99-0a6f-4271-bef2-e80eeafdf357)" />
				</svg>
				<svg
					class="absolute top-1/2 right-full transform -translate-y-1/2 -translate-x-32"
					width="404"
					height="384"
					fill="none"
					viewBox="0 0 404 384"
				>
					<defs>
						<pattern
							id="f210dbf6-a58d-4871-961e-36d5016a0f49"
							x="0"
							y="0"
							width="20"
							height="20"
							patternUnits="userSpaceOnUse"
						>
							<rect x="0" y="0" width="4" height="4" class="text-tertiary" fill="currentColor" />
						</pattern>
					</defs>
					<rect width="404" height="384" fill="url(#f210dbf6-a58d-4871-961e-36d5016a0f49)" />
				</svg>
				<svg
					class="absolute bottom-12 left-full transform translate-x-32"
					width="404"
					height="384"
					fill="none"
					viewBox="0 0 404 384"
				>
					<defs>
						<pattern
							id="d3eb07ae-5182-43e6-857d-35c643af9034"
							x="0"
							y="0"
							width="20"
							height="20"
							patternUnits="userSpaceOnUse"
						>
							<rect x="0" y="0" width="4" height="4" class="text-tertiary" fill="currentColor" />
						</pattern>
					</defs>
					<rect width="404" height="384" fill="url(#d3eb07ae-5182-43e6-857d-35c643af9034)" />
				</svg>
			</div>
		</div>
		<div class="relative px-4 sm:px-6 lg:px-8">
			<div class="text-lg max-w-prose mx-auto">
				<slot />
				<!-- <div class="text-lg max-w-prose mx-auto">
            <h1>
				<span class="block text-base text-center text-indigo-600 font-semibold tracking-wide uppercase">Introducing</span>
				<span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">JavaScript for Beginners</span>
            </h1>
            <p class="mt-8 text-xl text-gray-500 leading-8">Aliquet nec orci mattis amet quisque ullamcorper neque, nibh sem. At arcu, sit dui mi, nibh dui, diam eget aliquam. Quisque id at vitae feugiat egestas ac. Diam nulla orci at in viverra scelerisque eget. Eleifend egestas fringilla sapien.</p>
		</div>
		<div class="mt-6 prose prose-indigo prose-lg text-gray-500 mx-auto">
            <p>Faucibus commodo massa rhoncus, volutpat. <strong>Dignissim</strong> sed <strong>eget risus enim</strong>. Mattis mauris semper sed amet vitae sed turpis id. Id dolor praesent donec est. Odio penatibus risus viverra tellus varius sit neque erat velit. Faucibus commodo massa rhoncus, volutpat. Dignissim sed eget risus enim. <a href="#">Mattis mauris semper</a> sed amet vitae sed turpis id.</p>
            <ul>
				<li>Quis elit egestas venenatis mattis dignissim.</li>
				<li>Cras cras lobortis vitae vivamus ultricies facilisis tempus.</li>
				<li>Orci in sit morbi dignissim metus diam arcu pretium.</li>
            </ul>
            <p>Quis semper vulputate aliquam venenatis egestas sagittis quisque orci. Donec commodo sit viverra aliquam porttitor ultrices gravida eu. Tincidunt leo, elementum mattis elementum ut nisl, justo, amet, mattis. Nunc purus, diam commodo tincidunt turpis. Amet, duis sed elit interdum dignissim.</p>
            <h2>From beginner to expert in 30 days</h2>
            <p>Id orci tellus laoreet id ac. Dolor, aenean leo, ac etiam consequat in. Convallis arcu ipsum urna nibh. Pharetra, euismod vitae interdum mauris enim, consequat vulputate nibh. Maecenas pellentesque id sed tellus mauris, ultrices mauris. Tincidunt enim cursus ridiculus mi. Pellentesque nam sed nullam sed diam turpis ipsum eu a sed convallis diam.</p>
            <blockquote>
				<p>Sagittis scelerisque nulla cursus in enim consectetur quam. Dictum urna sed consectetur neque tristique pellentesque. Blandit amet, sed aenean erat arcu morbi.</p>
            </blockquote>
            <p>Faucibus commodo massa rhoncus, volutpat. Dignissim sed eget risus enim. Mattis mauris semper sed amet vitae sed turpis id. Id dolor praesent donec est. Odio penatibus risus viverra tellus varius sit neque erat velit.</p>
            <figure>
				<img class="w-full rounded-lg" src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&auto=format&fit=facearea&w=1310&h=873&q=80&facepad=3" alt="" width="1310" height="873">
				<figcaption>Sagittis scelerisque nulla cursus in enim consectetur quam.</figcaption>
            </figure>
            <h2>Everything you need to get up and running</h2>
            <p>Purus morbi dignissim senectus mattis <a href="#">adipiscing</a>. Amet, massa quam varius orci dapibus volutpat cras. In amet eu ridiculus leo sodales cursus tristique. Tincidunt sed tempus ut viverra ridiculus non molestie. Gravida quis fringilla amet eget dui tempor dignissim. Facilisis auctor venenatis varius nunc, congue erat ac. Cras fermentum convallis quam.</p>
            <p>Faucibus commodo massa rhoncus, volutpat. Dignissim sed eget risus enim. Mattis mauris semper sed amet vitae sed turpis id. Id dolor praesent donec est. Odio penatibus risus viverra tellus varius sit neque erat velit.</p> -->
				<div class="mt-10" id="disqus_thread" />
			</div>
		</div>
	</div>
</div>
