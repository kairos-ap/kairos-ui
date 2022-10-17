<script lang="ts">
	import '../app.pcss';

	import NavBar from '$components/navigation/NavBar.svelte';
	import NavBarBrand from '$components/navigation/NavBarBrand.svelte';
</script>

<NavBar>
	<NavBarBrand>
		<a href="/"> 🗓️ Kaïros </a>
	</NavBarBrand>
</NavBar>

<slot />
