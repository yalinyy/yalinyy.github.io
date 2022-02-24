---
title: css属性之text-align-last
date: 2022-02-23 12:00:24
tags:
---
   
一次偶然的机会看到了 “text-align-last” 这个css属性，本着学习的态度查看了相关资料。

#### 什么是text-align-last？
CSS 属性 text-align-last  描述的是一段文本中最后一行在被强制换行之前的对齐规则。

<font color="red">请注意：</font>text-align-last 属性设置的是被选元素内的所有最末行。所以，如果一个 <div> 中有三个段落，text-align-last 会应用于每段的最后一行。如需在容器中的最后一段上使用 text-align-last，您可使用 :last child。

#### text-align-last有哪些属性值？
  1. auto
		*	每一行的对齐规则由 text-align 的值来确定。
		*  经测试，当 text-align 的值为 right，并且 text-align-last 设置为 auto 时，文本最后一行的对齐方式相当于 text-align-last 被设置为 right 时的效果。
  2. start
    	* 最后一行在行起点对齐。

  3. end
      * 最后一行在行末尾对齐。
  4. left
      * 最后一行向左对齐。
  5. right
		*	最后一行文字与内容盒子的右侧对齐
  6. center
		*	最后一行文字与内容盒子居中对齐
  7. justify
		*	最后一行文字的开头与内容盒子的左侧对齐，末尾与右侧对齐。s

#### 浏览器兼容性
![浏览器兼容性](https://img-blog.csdnimg.cn/5903c6725c934667b5c37b88cd60eb1b.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA5LiA5Liq5YWl6Zeo57qn55qE56iL5bqP54y_,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)




######  参考链接
1. https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-align-last