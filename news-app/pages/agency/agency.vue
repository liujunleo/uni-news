<!-- 网络链接内容展示页（uni-id-pages中用于展示隐私政策协议内容） -->
<template>
	<view>
		<web-view src="https://www.baidu.com"></web-view>
	</view>
</template>

<script>
	export default {
		onLoad() {
			uni.setNavigationBarTitle({title: '人民号'});
		}
	}
</script>
