<template>
	<Navbar/>

	<div class="d-flex">
		<div class="col-4">
			<EntryList/>
		</div>
		<div class="col">
			<router-view/>
		</div>
	</div>
</template>

<script>
	import Navbar from '../components/Navbar.vue'
	import EntryList from '../components/EntryList.vue'
export default {
	components: {
		Navbar,
		EntryList
	}
}
</script>

<style lang="css" scoped>
</style>