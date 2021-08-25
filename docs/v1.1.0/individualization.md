# 个性化
对颜色等样式不满意？按照指南进行修改吧
```
.wd{
	border: 1px #d9d9d9 solid;
	box-shadow:3px 3px 3px #909090;
	margin-top: 44px;
	background-color: #86BA4B;
	animation-duration: 3s;  
	-webkit-animation-duration: 3s;
}
.wd>.picture{
	width: [宽];
	height: [高];
	z-index: 2;
	padding-left: 15px;
	padding-right: 149px;
	position:relative;
}
/* div */
.wd>.picture>.text>.title{
	margin-top: 7px;
}
.wd>.picture>.text{
	background: rgba(0,0,0,.5);
	opacity: 1;
	position:absolute;
	bottom:0;
	right: 0;
	left: 0;
	padding-bottom: 3px;
}
/* p */
.wd>.picture>.text>p{
	margin-bottom: 0px;
	color: #FFFF00;
	margin-left: 8px;
}
.wd>.picture>.text>.title>p{
	color: [文字颜色];
	/* margin-bottom: 0px; */
	font-size: [文字大小];
	margin-left: 8px;
	margin-bottom: 0px;
}
/* top */
.wd>.picture>.top-text>.top-right-text{
	position: absolute;
	right: 0;
	margin-top: -19px;
}
.wd>.picture>.top-text>.top-button-text{
	margin-top: 16px;
}
.wd>.picture>.top-text>.top-right-text>p{
	color: [上文字颜色];
	margin-bottom: 2px;
	margin-right: 10px;
	margin-top: 5px;
}
.wd>.picture>.top-text>.top-button-text>p{
	color: [上文字颜色];
	margin-bottom: 0px;
}
```