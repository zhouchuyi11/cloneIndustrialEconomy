<template>
	<div class="home">
		<div class="left">
			<div class="left-1-title">
				<span class="title">预测预警总览</span>
				<div class="item-dropdown">
					<a-dropdown>
						<a class="ant-dropdown-link" @click.prevent>
							本周
							<DownOutlined />
						</a>
						<template #overlay>
							<a-menu click="menu">
								<a-menu-item>
									<a href="javascript:;">本月</a>
								</a-menu-item>
								<a-menu-item>
									<a href="javascript:;">本季</a>
								</a-menu-item>
								<a-menu-item>
									<a href="javascript:;">本年</a>
								</a-menu-item>
							</a-menu>
						</template>
					</a-dropdown>
				</div>
			</div>
			<div class="left-1">
				<div class="left-1-item">
					<div class="left-1-item-title">
						<img class="img1" src="@/assets/images/item-1-1.png" />
						<span>预测产值增速</span>
					</div>
					<div class="left-1-item-main">
						<img class="img2" src="@/assets/images/arrowhead-green.png" />
						<span class="data1">10</span>
						<span class="data2">%</span>
					</div>
				</div>
				<div class="left-1-item">
					<div class="left-1-item-title">
						<img class="img1" src="@/assets/images/item-1-2.png" />
						<span>全市总电量</span>
					</div>
					<div class="left-1-item-main">
						<span class="data1">21,320</span>
						<span class="text">亿kwh</span>
					</div>
				</div>
				<div class="left-1-item">
					<div class="left-1-item-title">
						<img class="img1" src="@/assets/images/item-1-3.png" />
						<span>同比增长</span>
					</div>
					<div class="left-1-item-main">
						<img class="img2" src="@/assets/images/arrowhead-blue.png" />
						<span class="data1">8</span>
						<span class="data2">%</span>
					</div>
				</div>
				<div class="left-1-item">
					<div class="left-1-item-title">
						<img class="img1" src="@/assets/images/item-1-4.png" />
						<span>环比增长</span>
					</div>
					<div class="left-1-item-main">
						<img class="img2" src="@/assets/images/arrowhead-purple.png" />
						<span class="data1">8</span>
						<span class="data2">%</span>
					</div>
				</div>
			</div>
			<div class="title">经济运行特点</div>
			<div class="left-2">
				<div class="left-2-item">
					<div class="item-title">
						<img src="@/assets/images/item-2-1.png" />
						<span>区县用电增长排行</span>
					</div>
					<div class="main">
						<div>
							<span class="uname">1.南湖区</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">2.秀洲区</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">3.桐乡区</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">4.海宁区</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green.png" />
								<span>2%</span>
							</span>
						</div>
					</div>
					<a-button class="seeAll" @click="toSeeAll">查看全部</a-button>
				</div>
				<div class="left-2-item">
					<div class="item-title">
						<img src="@/assets/images/item-2-2.png" />
						<span>315N集群增长排行</span>
					</div>
					<div class="main">
						<div>
							<span class="uname">1.新能源</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green-down.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">2.新材料</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green-down.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">3.智能光伏</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green-down.png" />
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">4.科技产业</span>
							<span class="data">
								<img src="@/assets/images/arrowhead-green-down.png" />
								<span>2%</span>
							</span>
						</div>
					</div>
					<a-button class="seeAll" @click="toSeeAll">查看全部</a-button>
				</div>
				<div class="left-2-item">
					<div class="item-title">
						<img src="@/assets/images/item-2-3.png" />
						<span>415x集群增长排行</span>
					</div>
					<div class="main">
						<div>
							<span class="uname">1.纺织服装</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">2.新材料</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">3.智能光伏</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">4.科技产业</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
					</div>
					<a-button class="seeAll" @click="toSeeAll">查看全部</a-button>
				</div>
				<div class="left-2-item">
					<div class="item-title">
						<img src="@/assets/images/item-2-4.png" />
						<span>行业大类增长排行</span>
					</div>
					<div class="main">
						<div>
							<span class="uname">1.纺织服装</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">2.新材料</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">3.智能光伏</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
						<div>
							<span class="uname">4.科技产业</span>
							<span class="data">
								<span>2%</span>
							</span>
						</div>
					</div>
					<a-button class="seeAll" @click="toSeeAll">查看全部</a-button>
				</div>
			</div>
			<div class="left3">
				<span class="title">重点关注行业</span>
				<a-button class="edit">编辑</a-button>
				<div class="item-right">
					<div class="content">
						<span class="text">全市工业增加值增长&emsp;</span>
						<img src="@/assets/images/circle-arrowhead-up.png" />
						<span class="data">14%</span>
					</div>
					<a-dropdown>
						<a class="ant-dropdown-link" @click.prevent>
							本周
							<!--							<a-icon slot="icon" type="caret-right" />-->
							<DownOutlined />
						</a>
						<template #overlay>
							<a-menu>
								<a-menu-item>
									<a href="typescript:;">本月</a>
								</a-menu-item>
								<a-menu-item>
									<a href="typescript:;">本季</a>
								</a-menu-item>
								<a-menu-item>
									<a href="typescript:;">本年</a>
								</a-menu-item>
							</a-menu>
						</template>
					</a-dropdown>
				</div>
			</div>
		</div>
		<div class="right">
			<div class="right-1">
				<div class="up">
					<div class="up-left">
						<div class="year">123</div>
						<div class="ename">总企业数</div>
					</div>
					<div class="up-right">21,320</div>
				</div>
				<hr />
				<div class="down">
					<div class="down-item">
						<a-button class="img-button button1">1</a-button>
						<div>企业</div>
					</div>
					<div class="down-item">
						<a-button class="img-button button2">2</a-button>
						<div>流水</div>
					</div>
					<div class="down-item">
						<a-button class="img-button button3">3</a-button>
						<div>报表</div>
					</div>
				</div>
			</div>
			<div class="right-2">
				<div class="right-2-title">
					<div class="tit">通知公告</div>
					<div><a-button class="more">更多></a-button></div>
				</div>
				<div class="right-2-item">
					<div class="scroll-items">
						<div class="item">
							<img src="@/assets/images/tongzhi.png" />
							<span
								>【市经信局 2023-06023】<br />政府、团体对重大事件当中正式公布或公开宣告，宣布章鱼哥为打工人之首，号召所有打工人像章鱼哥看齐，不要委屈了自己，人哪有不疯的，强撑罢了</span
							>
						</div>
						<div class="item">
							<img src="@/assets/images/tongzhi.png" />
							<span
								>【市经信局 2023-06023】<br />政府、团体对重大事件当中正式公布或公开宣告，宣布章鱼哥为打工人之首，号召所有打工人像章鱼哥看齐，不要委屈了自己，人哪有不疯的，强撑罢了</span
							>
						</div>
						<div class="item">
							<img src="@/assets/images/tongzhi.png" />
							<span
								>【市经信局 2023-06023】<br />政府、团体对重大事件当中正式公布或公开宣告，宣布章鱼哥为打工人之首，号召所有打工人像章鱼哥看齐，不要委屈了自己，人哪有不疯的，强撑罢了</span
							>
						</div>
					</div>
				</div>
			</div>
			<div class="right-3">
				<div class="right-3-title">
					<span> 大企业用电排行 </span>
					<a-button class="more">更多></a-button>
				</div>
				<div class="right-3-item">
					<div class="img">1</div>
					<div class="text">纺织行业...</div>
				</div>
				<div class="right-3-item">
					<div class="img">2</div>
					<div class="text">制造业</div>
				</div>
				<div class="right-3-item">
					<div class="img">3</div>
					<div class="text">新材料</div>
				</div>
				<div class="right-3-item">
					<div class="img">4</div>
					<div class="text">纺织行业...</div>
				</div>
				<div class="right-3-item">
					<div class="img">5</div>
					<div class="text">纺织行业...</div>
				</div>
			</div>
		</div>
	</div>
</template>
<script lang="ts" setup>
import { ref } from 'vue'
import { DownOutlined } from '@ant-design/icons-vue'
import { useRouter } from 'vue-router'

function toSeeAll() {
	const router = useRouter()
	router.push({
		path: '/'
	})
}
</script>
<style lang="scss" scoped>
@import '@/assets/scss/mixins.scss';
$valueColors: #18ac9c #18184f #45affe #4b5bfa;
.home {
	@include wh(89vw, 93vh);
	@include flexMixin(space-around, center);
	background-color: #fafafa;
	.left {
		@include wh(100%, 100%);
		flex: 0 0 75%;
		.title {
			@include fontMixin(1.25vw, bold, #333);
			font-family: 'PingFang SC';
			line-height: 3.5vw;
			margin-left: 1.67vw;
		}
		.ant-dropdown-link {
			text-align: center;
			@include wh(4.43vw, 1.82vw);
			background-color: #e0e4ee;
			border-radius: 0.94vw;
			@include fontMixin(0.94vw, bold, #2c3345);
			font-family: 'PingFang SC';
			line-height: 1.8vw;
		}
		.left-1-title {
			.item-dropdown {
				display: flex;
				margin-top: 1vw;
				float: right;
			}
		}
		.left-1 {
			width: 100%;
			@include flexMixin(space-around, center);
			@each $color in $valueColors {
				$index: index($valueColors, $color);
				div:nth-child(#{$index}) {
					flex-basis: 25%;
					text-align: center;
					.left-1-item-title {
						.img1 {
							@include wh(1.3vw, 1.3vw);
							margin-right: 0.47vw;
						}
						span {
							@include fontMixin(0.83vw, bold, #333);
							font-family: PingFang SC;
							line-height: 2.5vw;
						}
					}
					.left-1-item-main {
						.img2 {
							@include wh(0.68vw, 1.61vw);
							margin-right: 0.25vw;
							margin-bottom: 1vw;
						}
						.data1 {
							@include fontMixin(2.19vw, bold, $color);
							font-family: 'DIN Alternate';
							//line-height: 13.28vw;
						}
						.data2 {
							@include fontMixin(2.19vw, normal, $color);
							font-family: 'DIN Alternate';
						}
						.text {
							@include fontMixin(1.2vw, normal, #18184f);
							font-family: 'Adobe Heiti Std';
							//line-height: 7.4vw;
						}
					}
				}
			}
		}
		.left-2 {
			width: 100%;
			@include flexMixin(space-around, center);
			.left-2-item {
				width: 13.75vw;
				//@include wh(13.75vw, 19vh);
				background-color: #fff;
				border-radius: 0.625vw;
				text-align: center;
				.item-title {
					margin-top: 0.5vw;
					img {
						@include wh(2.19vw, 2.19vw);
						margin-right: 0.42vw;
						//vertical-align: middle;
					}
					span {
						@include fontMixin(0.73vw, bold, #2c3345);
						font-family: 'PingFang SC';
						line-height: 3.49vw;
						margin-top: 1.25vw;
						//display: inline-block;
					}
				}
				.main {
					@include flexMixin(space-around, center, column);
					div {
						width: 70%;
						.uname {
							float: left;
							@include fontMixin(0.73vw, medium, #767d88);
							text-align: start;
							font-family: 'PingFang SC';
							margin-top: 0.25vw;
							text-overflow: ellipsis;
							width: 4.5vw;
							white-space: nowrap;
							overflow: hidden;
						}
						.data {
							display: block;
							float: right;
							img {
								@include wh(0.26vw, 0.57vw);
								//vertical-align: middle;
								margin-right: 0.15vw;
							}
							span {
								display: inline-block;
								@include fontMixin(0.73vw, medium, #767d88);
								font-family: 'PingFang SC';
								//vertical-align: top;
							}
						}
					}
				}
				.seeAll {
					border: none;
					margin: 1.25vw 0;
					@include wh(75%, 1.93vw);
					background-color: #f1f5fd;
					border-radius: 0.37vw;
					@include fontMixin(0.73vw, bold, #7fa0f9);
					font-family: 'PingFang SC';
					//line-height: 3.5vw;
				}
				[ant-click-animating-without-extra-node]:after {
					-webkit-animation: none !important;
					-moz-animation: none !important;
					-o-animation: none !important;
					-ms-animation: none !important;
					animation: none !important;
				}
			}
		}
		.left3 {
			.edit {
				border: none;
				@include wh(3.97vw, 1.5vw);
				background-color: #e3ebff;
				border-radius: 0.2vw;
				@include fontMixin(0.73vw, bold, #7fa0f9);
				font-family: 'PingFang SC';
				margin-left: 0.625vw;
				//line-height: 3.5vw;
				text-align: center;
			}
			[ant-click-animating-without-extra-node]:after {
				-webkit-animation: none !important;
				-moz-animation: none !important;
				-o-animation: none !important;
				-ms-animation: none !important;
				animation: none !important;
			}
			.item-right {
				@include flexMixin(space-between, center);
				margin-top: 1.25vw;
				float: right;
				gap: 1.15vw;
				.content {
					width: 14.12vw;
					//@include wh(14.12vw, 1.82vw);
					background-color: #edf2fd;
					border-radius: 0.2vw;
					text-align: center;
					text-overflow: ellipsis;
					white-space: nowrap;
					overflow: hidden;
					.text {
						@include fontMixin(0.83vw, normal, #7fa0f9);
						font-family: 'PingFang SC';
						line-height: 1.5vw;
					}
					img {
						@include wh(0.83vw, 0.83vw);
						vertical-align: middle;
					}
					.data {
						@include fontMixin(0.83vw, bold, #18ac9c);
						font-family: 'PingFang SC';
						//display: inline-block;
					}
				}
			}
		}
	}
	.right {
		@include wh(100%, 100%);
		flex: 0 0 25%;
		@include flexMixin(flex-start, center, column);
		gap: 0.8vw;

		.right-1 {
			@include wh(17vw, 14vw);
			background-color: #3f75ff;
			border-radius: 1.4vw;
			margin-top: 0.8vw;
			.up {
				@include flexMixin(space-around, center);
				height: 40%;
				.up-left {
					.year {
						@include fontMixin(0.73vw, bold, #fff);
						font-family: 'PingFang SC';
						//line-height: 3.5vw;
						opacity: 0.7;
					}
					.ename {
						@include fontMixin(0.94vw, bold, #fff);
						font-family: 'PingFang SC';
						//line-height: 3.5vw;
					}
				}
				.up-right {
					@include fontMixin(2.2vw, bold, #fff);
					font-family: 'DIN Alternate';
					//line-height: 13.3vw;
					text-align: center;
				}
			}
			hr {
				@include wh(13.9vw, 0.05vw);
				background-color: #ffffff;
				opacity: 0.2;
				border: none;
			}
			.down {
				@include flexMixin(center, flex-end);
				height: 42%;
				gap: 1.7vw;
				.down-item {
					.img-button {
						@include wh(3.54vw, 3.54vw);
						border-radius: 50%;
						border: none;
						font-size: 0;
					}
					.button1 {
						background: url('@/assets/images/item-qiye.png');
						background-size: 100%;
					}
					.button2 {
						background: url('@/assets/images/item-liushui.png');
						background-size: 100%;
					}
					.button3 {
						background: url('@/assets/images/item-baobiao.png');
						background-size: 100%;
					}
					img {
						@include wh(3.54vw, 3.54vw);
						vertical-align: bottom;
					}
					div {
						@include fontMixin(0.94vw, normal, #fff);
						font-family: 'Adobe Heiti Std';
						//line-height: 3.5vw;
						text-align: center;
					}
				}
			}
		}
		.right-2 {
			@include wh(17vw, 10.52vw);
			background-color: #ecf0fb;
			border-radius: 1.4vw;
			@include flexMixin(center, center, column);
			gap: 0.5vw;
			.right-2-title {
				@include flexMixin(space-between, center);
				width: 14.27vw;
				.tit {
					@include fontMixin(1.05vw, bold, #333);
					font-family: 'PingFang SC';
					//line-height: 2vw;
				}
				.more {
					background-color: transparent;
					border-style: none;
					@include fontMixin(0.5vw, bold, #3f75ff);
				}
				[ant-click-animating-without-extra-node]:after {
					-webkit-animation: none !important;
					-moz-animation: none !important;
					-o-animation: none !important;
					-ms-animation: none !important;
					animation: none !important;
				}
			}
			.right-2-item {
				position: relative;
				@include wh(14.27vw, 5.2vw);
				overflow: hidden;
				.scroll-items {
					position: absolute;
					top: 0;
					left: 0;
					width: 100%;
					animation: scroll 10s linear infinite normal;
					.item {
						width: 100%;
						background-color: #ffffff;
						border-radius: 0.3vw;
						text-align: center;
						padding: 0 0.1vw;
						margin-bottom: 1vw;
						img {
							@include wh(0.94vw, 0.94vw);
						}
						span {
							@include fontMixin(0.94vw, bold, #767d88);
							font-family: 'PingFang SC';
							line-height: 1.5vw;
						}
					}
				}
			}
			@keyframes scroll {
				100% {
					/* 需要滚动内容的总高度 */
					top: -300px;
				}
			}
		}
		.right-3 {
			@include wh(17vw, 26.35vw);
			background-color: #ecf0fb;
			border-radius: 1.4vw;
			@include flexMixin(center, center, column);
			gap: 0.8vw;
			.right-3-title {
				@include flexMixin(space-between, center);
				@include wh(14.27vw, 3.23vw);
				//line-height: 5vw;
				vertical-align: bottom;
				span {
					display: inline-block;
					width: 9vw;
					@include fontMixin(1.05vw, bold, #333);
					font-family: 'PingFang SC';
					text-overflow: ellipsis;
					overflow: hidden;
					word-break: break-all;
					white-space: nowrap;
				}
				.more {
					background-color: transparent;
					border-style: none;
					@include fontMixin(0.5vw, bold, #3f75ff);
				}
				[ant-click-animating-without-extra-node]:after {
					-webkit-animation: none !important;
					-moz-animation: none !important;
					-o-animation: none !important;
					-ms-animation: none !important;
					animation: none !important;
				}
			}
			.right-3-item {
				@include flexMixin(flex-start, center);
				@include wh(14.27vw, 3.23vw);
				background-color: #ffffff;
				border-radius: 0.32vw;
				.img {
					@include wh(1.67vw, 1.67vw);
					background-color: #eaefff;
					border-radius: 50%;
					text-align: center;
					@include fontMixin(1.05vw, normal, #736bcb);
					font-family: 'DIN Black';
					//line-height: 3.5vw;
					margin-left: 0.89vw;
					margin-right: 0.57vw;
				}
				.text {
					@include fontMixin(0.94vw, bold, #333);
					font-family: 'PingFang SC';
					//line-height: 3.5vw;
				}
			}
		}
	}
}
</style>
