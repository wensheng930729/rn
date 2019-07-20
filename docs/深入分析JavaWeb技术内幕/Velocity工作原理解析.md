# Velocity工作原理解析
+ Velocity架构
---
![velocity架构](pictures/velocity架构.png)
+ JJTree渲染过程解析
+ 事件处理机制
+ 常用优化技巧
	+ 减少树的总结点数量
	+ 减少渲染耗时的节点数量
+ Velocity vs JSP
---
![velocityVSjsp](pictures/velocityVSjsp.png)
+ 设计模式
	+ 合成模式(JavaCC将vm模板解析成抽象语法树)
	+ 解释器模式(将vm模板中的语句解析成一颗AST抽象语法树)