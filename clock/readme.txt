利用js实现小时钟：
其实没有想象中的那么复杂。
并不像是走了60s，然后控制分针走6°。
实现的原理是：
1.时针，分针，秒针分别控制自己。(找到时针分针秒针的ID)
2.获取当前的时间：精确为时，分，秒。
3.在setInterval函数的控制下，每一分钟时针，分针，秒针走的度数。
其实在后期，css3中很多动画是可以直接用样式来实现的，不需要用js