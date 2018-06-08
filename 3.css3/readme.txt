复合属性
animation-name
animation-duration
@keyframes  名称{
	0%{}
	25%{}
	50%{}
	75%{}
	100%{}
}
animation:
@keyframes testanimations{
	from{opacity:1;}
	to{opacity:0;}
}
@keyframes testanimations{
	from{transform:translate(0,0);}
	20%{transform:translate(20,20);}
	40%{transform:translate(40,0);}
	60%{transform:translate(60,20);}
	80%{transform:translate(80,0);}
	to{transform:translate(100,20);}



@keyframes testanimations{
	0%{transform:translate(0,0);}
	20%{transform:translate(20,20);}
	40%{transform:translate(40,0);}
	60%{transform:translate(60,20);}
	80%{transform:translate(80,0);}
	100%{transform:translate(100,20);}
}
transition: all 1s linear .3s;
/*transition:属性 运动时间 运动方式 延迟时间;*/

rotate 只能用deg单位
translateX/Y-----xy轴平移
transform:translate(100px,0px)
scale缩放比例
transform: scale(2,1)----x,y放大


z-index:999;要与position属性连用才能生效


box-sizing：border-box;和padding连用的时候，
padding值不会加在盒子里面



CSS3中translate、transform和translation的区别和联系
transform:变形。改变(静态的)
                 CSS3中主要包括 旋转：rotate() 顺时针旋转给定的角度，允许负值 rotate(30deg)
                   扭曲：skew() 元素翻转给定的角度,根据给定的水平线（X 轴）和垂直线（Y 轴）：skew(30deg,20deg)
                   缩放：scale() 放大或缩小，根据给定的宽度（X 轴）和高度（Y 轴）： scale(2,4)
                   移动：translate() 平移，传进 x,y值，代表沿x轴和y轴平移的距离
           改变起点位置 transform-origin: bottom left;

translate（）只是transform中的一个属性"平移"

transition: 允许CSS属性值在一定的时间区间内平滑的过渡(动态的，一次触发一次)
            需要事件的触发，例如单击、获取焦点、失去焦点等
             transition:property duration timing-function delay;
                   property:CSS的属性，例如：width height 为none时停止所有的运动，可以为transform
                   duration:持续时间
                   timing-function:ease linear等
                   delay:延迟
                   注意：当property为all的时候指所有动画
            例如：transition:width 2s ease 0s;

animation代表了一个动画(动态多次的)
				animation-name	规定需要绑定到选择器的 keyframe 名称。
				animation-duration	规定完成动画所花费的时间，以秒或毫秒计。
				animation-timing-function	规定动画的速度曲线。
				animation-delay	规定在动画开始之前的延迟。
				animation-iteration-count	规定动画应该播放的次数 ：infinite
				animation-direction	规定是否应该轮流反向播放动画。
		选择器{
			...
			...
			...
			animation: move 3s linear;
			}
		@keyframes move{
			from{

			}
			to{

			}
		}



perspective 属性定义 3D 元素距视图的距离，以像素px计。
			该属性允许您改变 3D 元素查看 3D 元素的视图。

当为元素定义 perspective 属性时，其子元素会获得透视效果，而不是元素本身


背景图片的尺寸background-size:100px 100px;
等比拉伸：backgroundsize:100px auto;

contain
cover等比拉伸(常用)


弹性布局


img间距8px
display:inline-block:间距8px
不常用
box-sizing:border-box/content-box(默认);
calc(公式)


win + T


