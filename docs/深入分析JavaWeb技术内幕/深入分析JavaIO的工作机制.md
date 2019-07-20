# 深入分析JavaI/O的工作机制
+ Java IO类
---
![IO类](pictures/io类.png)
+ 磁盘IO工作机制
	+ 访问文件的方式
		+ 标准文件访问方式
		---
		![标准文件访问方式](pictures/标准文件访问方式.png)
	    + 直接IO的方式(如数据库数据读写)
	    ---
	    ![直接io](pictures/直接io.png)
	    + 同步访问文件
	    + 异步访问文件
	    + 内存映射
	+ Java访问磁盘文件
	---
	![Java访问磁盘文件](pictures/Java访问磁盘文件.png)
+ 网络IO工作机制
	+ TCP连接过程状态转化
	---
	![tcp状态转化](pictures/tcp状态转化.png)
	---
	![tcp状态1](pictures/tcp状态1.png)
	---
	![tcp状态2](pictures/tcp状态2.png)
	+ 给于NIO的Socket请求处理过程
	---
	![socket-nio](pictures/socket-nio.png)