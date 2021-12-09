<script context="module" lang="ts">
    import Beer from "src/icons/Beer.svelte";
	import Coffee from "src/icons/Coffee.svelte";
	import Rhum from "src/icons/Rhum.svelte";

    export const prerender = true;
</script>
<div class="container w-11/12 lg:w-6/12 mx-auto m-6 p-3 rounded border border-secondary">
	<h1 class="text-3xl pb-5">The NoTrack project</h1>
	The No-Track project is a set of tools that can be used :
	<ul class="list-disc list-inside pt-2 pb-2">
		<li>For free</li>
		<li>Without any ads</li>
		<li>Without any tracking</li>
	</ul>
	The only limitation is a rate limit to avoid spam.<br />
	I hope you will use it with respect of the work being done.

	<h2 class="text-2xl pt-3 pb-2">What is the 12ft.io sharing bridge ?</h2>
	It's a very simple tool that allows you to forward a web page with a paywall to 12ft.io.<br />
	Simply using your smartphone native share function.

	<h2 class="text-2xl pt-3 pb-2">What is tracked ?</h2>
	Short answer is nothing. The long answer is, of course there are some technical logs on the servers,
	but without any user informations.<br />
	Nothing else :)<br />
	If you want to be sure of that, you can check by yourself on
	<a href="https://github.com/olibos/Acme.NoTrack.12ft">this repository</a>.

	<h2 class="text-2xl pt-3 pb-2">Free to use, but not to run</h2>
	Of course, these tools are not free to run. I make these because I really like the "Old Fashion" web,
	where everything was free and without ads.

	<div class="pt-2">
		If you want to support this project, you are welcome to :

		<div class="text-center">
			<a
				class="w-64 mx-auto mt-4 mb-4 py-2 px-4 bg-secondary text-white text-center font-semibold rounded-lg shadow-md border border-secondary hover:border-primary focus:outline-none inline-flex items-center"
				href="https://buy.stripe.com/bIYcNA755bBK2nC144"
				><Coffee /> Buy me a coffee (2.5€)</a
			>
		</div>
		<div class="text-center">
			<a
				class="w-64 mx-auto mt-4 mb-4 py-2 px-4 bg-secondary text-white text-center font-semibold rounded-lg shadow-md border border-secondary hover:border-primary focus:outline-none inline-flex items-center"
				href="https://buy.stripe.com/3csdREbllfS05zO5kl"
				><Beer /> Buy me a beer (5.0€)</a
			>
		</div>
		<div class="text-center">
			<a
				class="w-64 mx-auto mt-4 mb-4 py-2 px-4 bg-secondary text-white text-center font-semibold rounded-lg shadow-md border border-secondary hover:border-primary focus:outline-none inline-flex items-center"
				href="https://buy.stripe.com/7sI6pc4WX35ed2g146"
				><Rhum /> Buy me a rhum (10.0€)</a
			>
		</div>
	</div>
	<h2 class="text-2xl pt-3 pb-2">Another way to support ?</h2>
	Yes, of course ! This is an open source project, you can fork it and add the feature you want. This
	is stored in GitHub :
	<a href="https://github.com/olibos/Acme.NoTrack.12ft">Acme.NoTrack.12ft</a>.

	<h2 class="text-2xl pt-3 pb-2">Bugs ? Support ?</h2>
	This project is made on personal time, with the use of beta version of
	<a href="https://kit.svelte.dev/">SvelteKit</a>. there can be bugs, I can take time to fix them.
	<br />
	So, you use this tool as is, without any guarantee. You can always open an issue in the GitHub below.
</div>
