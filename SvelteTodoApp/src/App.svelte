<script>
	import Todo from "./Todo.svelte";
	import { onMount } from 'svelte';
    import axios from 'axios';
    
    let isError = null;
    let todos = [];
	export let name;

</script>

<main>
	<Todo />
</main>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
  </style>