<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<h1>SAAS with SvelteKit & Supabase</h1>
<p>A demo Software as a Service solution, using SvelteKit & Supabase</p>

<p>Supabase REST API URL: {data.supabaseUrl}</p>
<p>Supabase ANON KEY: {data.supabaseAnonKey}</p>
