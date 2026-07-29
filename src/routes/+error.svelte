<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Error {page.status}</h1>
	<p>{page.error?.message ?? "Something went wrong. Please try again."}</p>
	<a href="/">Return to Mariana Research</a>
</main>
