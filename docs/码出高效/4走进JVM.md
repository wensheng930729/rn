# 走进JVM
+ 类的二进制字节码
---
![类的二进制字节码](pictures/类的二进制字节码.png)
+ Java源码转字节码
---
![Java源码转字节码](pictures/Java源码转字节码.png)
+ 即时编译流程
---
![即时编译流程](pictures/即时编译流程.png)
+ Java类加载过程
---
![Java类加载过程](pictures/Java类加载过程.png)
+ 类加载的双亲委派模型
---
![类加载的双亲委派模型](pictures/类加载的双亲委派模型.png)
+ 需要自定义类加载器的情况
	+ 隔离加载类
	+ 修改类加载方式
	+ 扩展加载源
	+ 防止源码泄露
+ 经典JVM内存布局
---
![经典JVM内存布局](pictures/经典JVM内存布局.png)
+ JVM运行参数
	+ -Xms256M(memory start,堆内存空间初始值)
	+ -Xmxl024M(memory max,堆内存空间最大值)
	+ XX:+HeapDumpOnOutOfMemoryError(让口瓜 遇到 OOM 异常时能输出堆内信息，)
+ 堆对象分配及简要GC
---
![堆对象分配及简要GC](pictures/堆对象分配及简要GC.png)
+ JVM操作栈
---
![操作栈](pictures/操作栈.png)
+ Java线程与内存
---
![Java线程与内存](pictures/Java线程与内存.png)
+ Java垃圾回收算法
	+ 标记-清除算法
	+ 标记-整理算法
	+ Mark-Copy算法
+ Java垃圾回收器
	+ servial垃圾回收器
	---
	![servial垃圾回收器](pictures/servial垃圾回收器.png)
	+ CMS回收器(Concurrent Mark Sweep Collector)
	+ G1回收器(Garbage-First Garbage Collector)
	---
	![G1回收器模型](pictures/G1回收器模型.png)