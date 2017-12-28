# flex
flex

-

- 组成
	
	包含两部分
	
	1.flex 容器

	对项目进行规范，让项目依据容器为参照物进行布局
	
	2.flex 项目
		
	对项目进行定义
		
- 容器
	
	伸缩容器不是块容器，因此有些设计用来控制块布局的属性，在伸缩布局中不适用，特别是多栏（column)，float，clear，vertical-align这些属性。
	
- 项目

	flex,由flex-grow,flex-shrink,flex-basis组成
	
	flex-grow: 根据主轴的剩余空间按比例分配给项目，重弄新计算宽度或者高度，默认为0，盒模型保持不变
	
	flex-shrink: 当容器的容量小于项目的总容量的时候，对项目进行比例缩小,没有负值
	
	flex-basis: 在进行上面两个操作之前，对项目的宽高进行重新绘制
	
	执行顺序：basis -> grow -> shrink
		
	

	