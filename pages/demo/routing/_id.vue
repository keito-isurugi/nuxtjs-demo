<template>
	<div>
		<h1>Routing ID</h1>
		<p>ID:{{ $route.params.id }}</p>
	</div>
</template>

<script>
export default {
  name: 'RoutingIdPage',
	created() {
    console.log(this.$route.params.id)
  }
}

</script>
