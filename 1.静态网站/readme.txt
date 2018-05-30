1.bfc模式，
怎么理解元素在
bfc环境下----
		overflow:hidden;
		float: left;
		display:inline-block;
		position: absolute;



		/*margin:3px 4px;*/
		/*上下 左右*/
		/*margin:10px 50px 20px;*/
		/*上 左右 下*/
		/*margin:10px 20px 30px 40px;*/
		/*上 右 下 左*/


		注意:两个div的margin左右的会相加，上下的会合并



		能用css的，坚决不用html 标签解决

		img中img 的默认margin ：8px

			outline-width: 0px;
			vertical-align: top;
			上下去间距
			
			border:0;
			float:left;
			左右去间距

	最小字体为9px，但常用最小字体是12px,太小容易看不见


	定位浮动啥的写第一行
	line-height写第二行


	background-repeat: no-repeat;
	/*bgr*/
	background-position: center center;
	/*bgp*/
	background-size: ;的使用
	1.length:100px,一个固定的值
	2.percentage:50%;
	3.cover:图片的最小边缩放到目标大小
	4.contain:图片的最大边缩放到目标大小
	/*bgs*/
轮播图的问题
图片比较窄的话可以用text-algin:center;
图片比较宽，超出屏幕范围的话可以用：
background-position: center;

	position: absolute;
	left:50%;
	margin-left:-宽度的/2;width/2



在js中还想使用html的语法时，只能使用Ctrl+E




&nbsp;空格实体
&lt;小于号   less than
&gt;大于号   great than


position 子绝父相

relative不脱离文档流的，相对于原本的位置
 top left 像素，百分比表示
 代码紧挨在一起

 absolute脱离标准文档流，相对于整个body进行定位


 fixed固定定位


定位问题
父级{position: absolute;top:数值 ;bottom:数值;}
子级{position: absolute;top:数值 ;bottom:数值;}
或
父级{position:relative;top:数值 ;bottom:数值;}
子级{position: absolute;top:数值 ;bottom:数值;}
只要父级是定位属性(position:absolute或者position:relative)，他的子元素为position:absolute;的时候就是相对于父类的相对定位




文本不溢出
			white-space: nowrap;
			/*强制在同一行内显示所有文本，直到文本结束或者遭遇br对象*/
			/*ofh*/
			overflow: hidden;
			/*toe*/
			-ms-text-overflow: ellipsis;
			text-overflow: ellipsis;
			/* 当对象内文本溢出时显示省略标记（...）。*/

居中对齐
		.container{
			position: absolute;
			top:50%;
			left:50%;
			margin-left: -180px;
			margin-top: -150px;/*记得为负值*/
			width: 360px;
			height: 300px;
			background: #ccc;
		}