<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorld msg="Welcome to Your Vue.js App" />
	<app-badge
		label="Approved"
		bgColor="rgba(0, 204, 102, 0.1)"
		color="#00CC66"
	/>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import AppBadge from "./components/app-badge/AppBadge.vue";

export default {
	name: "App",
	components: {
		HelloWorld,
		AppBadge,
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
