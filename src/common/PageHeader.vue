<template>
	<header class="common-header">
		<!-- 导航 -->
		<PageNav />
		
	</header>
</template>

<script>
	import PageNav from './PageNav.vue'
	
	export default {
	  name: 'PageHeader',
	  components: {
		  PageNav
	  }
	}
</script>

<style>
	
	.common-header{
		position: fixed;
		background-color: #ffffff;
		top: 0;
		left: 0;
		padding: 0 10%;
		width: 100%;
		box-shadow: 0 1px 1px rgb(0 0 0 / 10%);
		box-sizing: content-box;
		z-index: 10;
	}
	
</style>
