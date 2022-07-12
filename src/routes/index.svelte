<script>
	import { goto } from '$app/navigation';
</script>

<div class="container py-3 mx-auto">
	<h1 class="py-4 text-2xl">Sveltekit Mobile Application</h1>

	<button class="px-3 py-2 border" on:click={() => goto('/option1')}>Options 1</button>
</div>
