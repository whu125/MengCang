<template>
	<div class="write_novel_page">
		<img src="../../static/jiantou.png" class="fanhuijiantou">
		<img src="../../static/guanbijiantou.png" class="guanbijiantou">
		<img src="../../static/write_novel_background.png" class="bg">
		<div class="write_novel_box">
			
			
			<div class="title">
				续   写   小   说
			</div>
			<div class="neikuang">
				<div class="liucheng">
					<div class="shangchuan_circle"></div>
					<div class="shangchuan_text">上传</div>
					<div class="lianxian1"></div>
					<div class="shenhe_circle"></div>
					<div class="shenhe_text">审核</div>
					<div class="lianxian2"></div>
					<div class="fabu_circle"></div>
					<div class="fabu_text">发布</div>
				</div>
				<text class="title_of_novel">书名xxx</text>
				<div class="shurukuang"></div>
				<div class="submit">上 传 续 写</div>
			</div>

		</div>
	</div>
</template>

<script> 
</script>

<style lang="scss" scoped>
.write_novel_page{
	position: relative;
	height: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}

.title{
	position: absolute;
	z-index: 2;
	top: 40rpx;
	text-align: center;
	letter-spacing: 0px;
	line-height: 0px;
	color: rgba(202, 182, 153, 1);
	text-align: center;
	vertical-align: middle;
	font-size: 25px;
	font-weight: 400;
	// border: 1px solid rgba(89, 46, 29, 1);            
}

.fanhuijiantou{
	position: absolute;
	height: 50rpx;
	top: 185rpx;
	left: 550rpx;
}

.guanbijiantou{
	position: absolute;
	height: 50rpx;
	top: 185rpx;
	left: 640rpx;
}

.write_novel_box{
	position: absolute;
	top:235rpx;
	height: 1210rpx;
	width: 720rpx;
	z-index: 1;
	opacity: 0.75;
	border-radius: 20rpx;
	background-image: url("../../static/续写小说文本框背景.jpg");
	border: 5rpx solid saddlebrown;
	display: flex;
	align-items: center;
	justify-content: center;
	}
.neikuang{
	position: absolute;
	top: 80rpx;
	height: 1130rpx;
	width: 718rpx;
	z-index: 1;
	// opacity: 0.55;
	border-radius: 10rpx;
	background: rgba(202, 182, 153, 1);
	display: flex;
	align-items: center;
	justify-content: center;
}
.liucheng{
	position: absolute;
	height: 200rpx;
	width: 660rpx;
	top: 90rpx;
	display: flex;
	align-items: center;
	justify-content: center;
}
.shangchuan_circle{
	position: absolute;
	top: 40rpx;
	border: 4rpx solid black;
	height: 20rpx;
	width: 20rpx;
	left: 66rpx;
	border-radius: 100rpx;
}
.shangchuan_text{
	left: 44rpx;
	position: absolute;
}
.shenhe_circle{
	position: absolute;
	top: 40rpx;
	border: 4rpx solid black;
	height: 20rpx;
	width: 20rpx;
	border-radius: 100rpx;
	background-color: black;
}
.shenhe_text{
	position: absolute;
}
.fabu_circle{
	position: absolute;
	top: 40rpx;
	border: 4rpx solid black;
	height: 20rpx;
	width: 20rpx;
	right: 66rpx;
	border-radius: 100rpx;
	background-color: black;
}
.fabu_text{
	position: absolute;
	right: 44rpx;
}
.lianxian1{
	position: absolute;
	border: 4rpx solid black;
	width: 220rpx;
	top: 49rpx;
	left: 90rpx;
	background: black;
}
.lianxian2{
	position: absolute;
	border: 4rpx solid black;
	width: 220rpx;
	top: 49rpx;
	right: 90rpx;
	background:black;
}
.title_of_novel{
	position: absolute;
	top: 290rpx;
	left: 50rpx;
	font-size: 44rpx;
}
.shurukuang{
	border: 7rpx solid black;
	position: absolute;
	top: 350rpx;
	height: 600rpx;
	width: 666rpx;
	border-radius: 50rpx;
	z-index: 3;
}
.submit{
	z-index: 3;
	position: absolute;
	background: saddlebrown;
	opacity: 1;
	top: 1000rpx;
	width: 660rpx;
	display: flex;
	align-items: center;
	justify-content: center;
	height: 90rpx;
	border: 2rpx solid black;
	border-radius: 50rpx;
	font-size: 44rpx;
}

.bg{
	width: 100%;
	height: 100%;
}
</style>
