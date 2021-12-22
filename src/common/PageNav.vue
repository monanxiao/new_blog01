<template>
	<nav class="header_nav">
		<a href="/" class="logo">
			<img src="http://www.ufoer.com/wp-content/uploads/2016/08/Snip20160809_19.png" alt="logo图片">
		</a>
		
		<ul class="header_nav_list">
			<li class="current">导航1</li>
			<li>导航1</li>
			<li>导航1</li>
			<li>导航1</li>
			<li>导航1</li>
		</ul>
	</nav>
</template>

<script>
</script>

<style>
	.header_nav{
		width: 80%;
		margin: 0 auto;
		display: flex;
		justify-content: flex-start;
	}
	
	.header_nav .logo{
		width: 110px;
		height: 60px;
		margin-right: 20px;
	}
	
	.header_nav .logo img{
		width: 100%;
		margin-top: 10px;
	}
	
	.header_nav_list{
		display: flex;
		justify-content: space-between;
	}
	
	.header_nav_list li{
		line-height: 60px;
		padding: 0px 15px;
		color: #3333333;
		margin: 0px 5px;
		font-size: 15px;
	}
	
	.header_nav_list .current{
		color: #ffffff;
		background: #E67E22;
		font-weight: 600;
	}
</style>
