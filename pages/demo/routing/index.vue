<template>
	<div>
		<h1>Routing Demo</h1>
		<NuxtLink to="/">Home page</NuxtLink><br>
		<a href="https://nuxtjs.org">External Link to another page</a><br>
		<NuxtLink to="/demo/routing/1">動的ルーティング</NuxtLink><br>
	</div>
</template>

<script>
export default {
  name: 'RoutingPage'
}
</script>
