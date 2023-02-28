<template>
	<div class="write_novel_page">
		<div class="top_background1"></div>
		<div class="top_background2"></div>
		<img src="../../static/top_jiantou.png" class="fanhuijiantou">
		<img src="../../static/people.png" class="people">
		<img src="../../static/write_novel_background_new.png" class="bg">
		<div class="peopleswords"></div>
		<div class="qipao1"></div>
		<div class="qipao2"></div>
		<div class="xuxiexiaoshuokuang"></div>
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

.top_background1{
	position: absolute;
	left: 0px;
	top: 0px;
	width: 120px;
	height: 25px;
	border-radius: 10rpx;
	background: rgba(119, 41, 255, 1);
	z-index: 1;
	border-width: 0px 5px 5px 0px;
	border-style: solid;
	border-color: rgba(255, 92, 255, 1);
}

.top_background2{
	position: absolute;
	z-index: 1;
	left: 120px;
	top: 0px;
	width: 375px;
	height: 15px;
	opacity: 1;
	background: rgba(119, 41, 255, 1);
	border: 5px solid rgba(255, 92, 255, 1);  
	border-width: 0rpx 0rpx 10rpx 0rpx; 
}

.people{
	left: 2px;
	top: 20px;
	width: 37%;
	height: 24%;
	opacity: 0.9;
	z-index: 2;
	position: absolute;
}

.peopleswords{
	position: absolute;
	left: 45%;
	top: 4%;
	width: 45%;
	height: 15%;
	opacity: 1;
	border-radius: 50px;
	background: rgba(121, 72, 234, 0.5);
	border: 3px solid rgba(251, 44, 255, 1);            
}

.qipao1{
	position: absolute;
	z-index: 3;
	left: 38%;
	top: 20%;
	width: 2%;
	height: 1%;
	opacity: 1;
	border-radius: 50px;
	background: rgba(121, 72, 234, 0.4);
	border: 2px solid rgba(251, 44, 255, 1);        
}

.qipao2{
	position: absolute;
	left: 43%;
	top: 18%;
	width: 2%;
	height: 1%;
	opacity: 1;
	border-radius: 50px;
	background: rgba(121, 72, 234, 0.4);
	border: 2px solid rgba(251, 44, 255, 1);        
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
	z-index: 1;
	height: 45rpx;
	width: 100rpx;
	top: 3rpx;
	left: 80rpx;
	-webkit-transform: rotate(180deg);
}

.xuxiexiaoshuokuang{
	position: absolute;
	top: 400rpx;
	height: 1155rpx;
	width: 700rpx;
	z-index: 1;
	background-image: url("../../static/input_background_brown_yellow.png");
	background-size: 100% 100%;
	
}

.liucheng{
	position: absolute;
	z-index: 1;
	height: 200rpx;
	width: 660rpx;
	top: 550rpx;
	display: flex;
	align-items: center;
	justify-content: center;
}

.title_of_novel{
	position: absolute;
	z-index: 1;
	top: 690rpx;
	left: 70rpx;
	font-size: 44rpx;
}

.shurukuang{
	border: 7rpx solid black;
	position: absolute;
	top: 770rpx;
	height: 500rpx;
	width: 580rpx;
	border-radius: 50rpx;
	background-color: navajowhite;
	z-index: 3;
}

.neikuang{
	position: absolute;
	top: 80rpx;
	height: 1130rpx;
	width: 718rpx;
	z-index: 1;
	// opacity: 0.55;
	border-radius: 10rpx;

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

.submit{
	z-index: 3;
	position: absolute;
	background: saddlebrown;
	opacity: 1;
	top: 1320rpx;
	width: 600rpx;
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
