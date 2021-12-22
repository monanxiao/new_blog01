<template>
	
  <PageHeader></PageHeader>
	
	<main class='home-main'>
		
		<router-view></router-view>
	</main>
	
  <PageFoot></PageFoot>
  
  
</template>

<script>
import PageHeader from './common/PageHeader.vue'
import PageFoot from './common/PageFoot.vue'

export default {
  name: 'App',
  components: {
    PageHeader,PageFoot
  }
}
</script>

<style>

	body,h1,h2,h3,h4,h5,li,a,ul{
		margin:0;
		padding: 0;
		text-decoration: none;
		list-style-type: none;
	}
	
	body{
		background-color: #e9eaec;
		font-family: "Lantinghei SC","Open Sans",Arial,"Hiragino Sans GB","Microsoft YaHei","微软雅黑","STHeiti","WenQuanYi Micro Hei",SimSun,sans-serif;
	}
	
	#app {
		position: relative;
	}
	
	.home-main{
		display: flex;
		justify-content: space-between;
		margin-top: 90px;
		min-width: 1170px;
		padding: 0 20%;
		box-sizing: border-box;
		margin-bottom: 80px;
	}
	
</style>
