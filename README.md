[详细中文文档请点击](http://www.kancloud.cn/houguang/scrollreveal/111473)

|属性|	默认值|	可选值|	描述|
| ---- | ---- | ---- | ---- |
|origin|	bottom	|'bottom', 'left', 'top', 'right'|	|
|distance|	20px|	'5rem', '10%', '20vw'|	可以设置任何有效的css距离|
|duration	|500|	Number	|动画持续时间|
|delay|	0|	Number|	动画延时执行时间，单位ms|
|rotate	|{ x : 0, y : 0, z : 0 }|	|	旋转角度|
|opacity|	0	||	元素开始时的透明度|
|scale|	0.9	||	元素开始时的缩放比例|
|easing|	cubic-bezier( 0.6, 0.2, 0.1, 1 )|	'ease', 'ease-in-out', 'linear'	|接收任何有效的CSS动画效果|
|container|	null||		当为空时，<html>被当做动画元素的容器。可以通过DOM结点来自定义值，例如：document.querySelector('.fooContainer');|
|mobile	|true|	true/false|	是否在移动端显示动画|
|reset	|False|	True/false|	是否每次出现在窗口中都执行动画|
|useDelay|	always|	'always','once','onload'|	 **'always'** 元素每次出现在窗口中时都使用延时动画  **'once'** 元素仅在第一次出现在窗口中时使用延时动画  **'onload'** 元素只有在第一次加载时使用延时动画|
|viewFactor|	0.2	|Float（0~1）	|元素被认为出现在窗口默认0.2，意思是元素出现在窗口中20%，元素必需是可见的。|
|viewOffset	|{ top : 0, right : 0, bottom : 0, left : 0 }||		元素距离窗口边界的像素值|
|afterReveal|	function( domEl ){}	||	元素每次执行完动画效果后调用。如果reset=true,元素每次完成动画后奖复位。当创建回调时，记得传递执行动画效果的第一个DOM元素。|
|afterReset	|function( domEl ){}||		同上一个参数|
