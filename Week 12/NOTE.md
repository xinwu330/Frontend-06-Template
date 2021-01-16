学习笔记

CSS排版三代排版技术：
	1. 正常流
	2. 基于Flex
	3. 基于Grid
	4. 3.5代 css houdini

CSS排版，两样：盒和文字正常流
	1. 收集盒和文字进行
	2. 计算盒在行中的排布
	3. 计算行的排布

IFC：从左往后，文字和inline-boxBFC：从上到下，line-box和block-level-box只有BFC会产生边距折叠 margin collposeBFC合并：
Block Container：所有能够容纳不是特殊display的
	* block
	* inline-block
	*table-cell
	* flex item
	* grid cell
	* table-caption


Block Box = 里外都有BFC
Block-level Box：
block level      inline level
   block         inline-block
   flex          inline-flex
   ...           ...

block box && overflow:visible
	* BFC合并与float
	* BFC合并与边距折叠



Flex排版
	* 收集盒进行
	* 计算盒在主轴方向的排布
	* 计算盒在交叉轴方向的排布


