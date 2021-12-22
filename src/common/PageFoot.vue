<template>
	<footer class="common_foot">
		<section class="common_main_foot">
			
			<section class="links">
				<h2>友情链接</h2>
				<section class="links_list">
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
					<a href="javascript:;">友情链接</a>
				</section>
				
			</section>
			
			<section class="tabs">
				<h2>热门标签</h2>
				<section class="tabs_list">
					<a href="javascript:;">标签</a>
					<a href="javascript:;">标签</a>
					<a href="javascript:;">标签</a>
					<a href="javascript:;">标签</a>
					<a href="javascript:;">标签</a>
					<a href="javascript:;">标签</a>
				</section>
				
			</section>
			
			<section class="wechat">
				<img src="../../static/img/wechat.jpg" alt="公众号">
				<p>扫码关注我</p>
			</section>
			
		</section>
		
		<section class="common_copyright_foot">
			<h2>Copyright © 2000-2021   版权所有：墨楠网站开发</h2>
		</section>
		
		<section class="security">
			<p>备案</p>
		</section>
	</footer>
</template>
	
<script>
	
	export default {
	  name: 'PageFoot',
	  components: {

	  }
	}
	
</script>

<style>
	
	.common_foot{
		background: #2d3237;
		height: auto;
		width: 100%;
		box-sizing: border-box;
	}
	
	.common_foot .common_main_foot{
		display: flex;
		justify-content: space-between;
		padding: 15px 20%;
	}
	
	.common_foot .common_main_foot .links>h2,
	.common_foot .common_main_foot .tabs>h2{
		color: #FFFFFF;
		font-size: 16px;
	}
	
	.common_foot .common_main_foot .links .links_list,
	.common_foot .common_main_foot .tabs .tabs_list{
		display: flex;
		justify-content: flex-start;
		flex-wrap: wrap;
	}
	.common_foot .common_main_foot .links .links_list>a{
		color: #F09D61;
		opacity: 0.6;
		padding: 10px 0px;
		padding-right: 30px;
		box-sizing: border-box;
	}
	
	.common_foot .common_main_foot .tabs .tabs_list>a{
		color: #F09D61;
		padding: 10px 0px;
		padding-right: 30px;
		box-sizing: border-box;
	}
	
	.common_foot .common_main_foot  .wechat{
	/* 	width: 140px;
		height: 140px; */
	}
	
	.common_foot .common_main_foot  .wechat p{
		text-align: center;
		color: #aaaaaa;
	}
	
	.common_foot .common_main_foot  .wechat>img{
		width: 140px;
		height: 140px;
	}
	
	.common_foot .common_copyright_foot{
		padding: 0px 20%;
		background-color: #23282d;
		box-sizing: border-box;
		text-align: center;
	}
	
	.common_foot .common_copyright_foot>h2{
		color: #666666;
		font-size: 14px;
		line-height: 50px;
	}
	
	.common_foot .security{
		background-color: #e9eaec;
		box-sizing: border-box;
		padding: 0px 20%;
	}
	
	.common_foot .security>p{
		line-height: 60px;
		margin: 0;
		text-align: center;
	}
</style>
