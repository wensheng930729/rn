# 深入分析ClassLoader工作机制
+ ClassLoader类结构分析：将二进制字节流解析成JVM能识别的class对象
+ ClassLoader的等级加载机制
	+ BootStrap ClassLoader
	+ ExtClassLoader
	+ AppClassLoader
+ JVM加载类的阶段
---
![jvm加载类的阶段](pictures/jvm加载类的阶段.png)