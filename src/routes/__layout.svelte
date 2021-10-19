<script>
	import AOS from 'aos';
	import { onMount } from 'svelte';

	import '../app.css';
	import 'aos/dist/aos.css';
	import '@fortawesome/fontawesome-free/css/all.css';

	onMount(() => {
		AOS.init();
	});
</script>

<slot />
