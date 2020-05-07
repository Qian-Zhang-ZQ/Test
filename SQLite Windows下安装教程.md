# SQLite Windows安装教程

本文档主要介绍 Windows 平台上SQLite的安装步骤。

### 下载文件

进入SQLite官网  <https://sqlite.org/download.html> 下载Windows平台下所需文件：**sqlite-dll-win32-x86-3310100.zip**；**sqlite-tools-win32-x86-3310100.zip**。

### 安装过程

1.首先将下载的两个.zip压缩包解压在同一个目录下，例如**D:\SQLite**; 得到 **sqlite3.def**、**sqlite3.dll **和**sqlite3.exe** ，**sqlite3_analyzer.exe**，**sqldiff.exe**文件

2.将该路径添加到环境变量里：

（1）右键**我的电脑**-**属性**-**高级系统设置**-**环境变量**，

（2） 在系统变量内找到“**Path**”，

（3） 点击**新建按钮**在其中添加SqLite文件夹的路径 **D:\SQLite** 添加到其中。

3.测试是否安装成功

在打开**cmd**，输入**sqlite3**，若如下显示打印**版本号**，则安装成功

~~~C:\Users\zuoxi>sqlite3
C:\Users\zuoxi>sqlite3
SQLite version 3.31.1 2020-01-27 19:55:54
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>
~~~



