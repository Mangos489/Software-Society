<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon_io/favicon.ico';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
//Make a superuser admin
//Run server 
//python .\manage.py makemigrations
//python .\manage.py migrate
//python .\manage.py runserver

{@render children?.()}
