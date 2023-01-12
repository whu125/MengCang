<template>

	<div class="bgBox">
		<!-- 似乎是太大了 在微信小程序里面显示不了 暂定做成app -->
		<img src="../../static/bg.jpg" alt="" class="bg">

		<div class="test"></div>
	</div>


</template>
<script setup lang="ts">
</script>
<style lang="scss" scoped>
	.bgBox {
		// padding-top: 20%;
		position: relative;
		height: 100%;
	}

	.bg {

		width: 100%;
		height: 100%;
	}

	.test {
		height: 30px;
		width: 100px;
		position: absolute;
		top: 560rpx;
		left: 70rpx;
		background: pink;
		z-index: 999;
	}
</style>
