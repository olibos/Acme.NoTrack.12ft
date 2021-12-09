<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import { onMount } from 'svelte';
	onMount(() => {
		const parsedUrl = new URL(window.location.toString()).searchParams;
		let url = (parsedUrl.get('url') || parsedUrl.get('text') || '').match(/https?:\S*/)?.[0];
		console.info('url', url);
		if (url) {
			location.replace(`https://12ft.io/${url}`);
		} else {
			window.close();
		}
	});
</script>
