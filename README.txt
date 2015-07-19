1.官方下载hadoop-2.6.0.tar.gz 解压到Windows系统 (D:\source\hadoop-2.6.0)

2.把 hadoop2.6.0-winutils 替换 D:\source\hadoop-2.6.0\bin

3.设置环境变量 HADOOP_HOME=D:\source\hadoop-2.6.0

4.PATH环境变量后面增加 ：PATH=....;%HADOOP_HOME%\bin

校验：
	打开cmd
	执行命令 hadoop
	
----------------------------------------------------

5.把hadoop-eclipse-plugin-2.6.0.jar加入到eclipse\plugin目录下

6.重启eclipse
