### 任务描述：
设计稿是有一定宽度的，这个宽度为页面的最小宽度，也就是说，当浏览器窗口宽度小于设计稿宽度时，允许出现横向滚动条，页面内容宽度保持不变，但是当浏览器窗口宽度大于设计稿宽度时，页面部分内容的宽度应该保持和浏览器窗口宽度一致，具体哪些部分题目不做具体指明，看看大家的判断如何。

借鉴：苹果官网

解决方案：头+8部分+尾（联系我们+版权）

问题1：psd获取材料

PS生成png图片素材，0顶头，1~9各部分，_0是背景大图， _1小图依次排列  

问题2：如何自适应,比1280还窄时出现横向滚动条

	min-width: 1280px;

Q2_1: 大屏展示，图片被横向拉伸

问题3：图片遮罩

Q4:去掉列表默认样式

	ul{list-style:none;}
列表元素横向排列

	li{float:left;}
Q5:文字竖直居中
	
	line-height:  px;


 