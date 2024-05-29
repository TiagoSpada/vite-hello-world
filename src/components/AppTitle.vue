<script>
export default {
	name: "AppTitle",
	data() {
		return {
			title: "La mia prima app con Vite!",
		};
	},
};
</script>
<template>
	<h1>{{ title }}</h1>
</template>
<style>
h1 {
	text-align: center;
	margin: auto;
	margin-top: 100px;
	max-width: 25%;
	border: 2px solid black;
	padding: 5px;
	border-radius: 10px;
}
</style>
