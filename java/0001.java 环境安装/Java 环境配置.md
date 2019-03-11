![景](http://www.liebrother.com/upload/b976c6d6da1540ce823cb8e1379f6ec8_01.jpg) 

准备出一套 Java 系列的学习教程，让自己重温一遍这几年来学到的知识，给自己一个机会去复盘这个学习过程，更重要的是想要帮助初学者少走弯路。

学习 Java 开发的同学第一门课就是安装 Java 开发环境。这里就给大家介绍一下这个过程。

## 下载 jdk

下载链接如下：
[jdk8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

下载完后解压，**解压后的路径不要有中文字符**，比如我解压后放在目录：C:\Software\Java\jdk1.8.0_152

## 配置环境变量

### 右击电脑、打开属性

![属性](http://www.liebrother.com/upload/ab4f109421334b48ac28327a86519bcc_01.jpg) 

### 高级系统设置

高级系统配置 --> 环境变量

![高级系统配置](http://www.liebrother.com/upload/ed51955c37e2437ca06e64b9812c76a1_03.jpg) 


#### 扩展

系统变量和用户变量的区别
用户变量：该配置的运行范围是你登陆计算机的用户
系统变量：该配置的运行范围是整个计算机的所有用户
如果你想在整个计算机的所有用户都可以应用到这些配置，则选择在系统变量中配置。

### 配置环境变量

需要配置如下 3 个环境变量。

| 变量名 | 变量值 | 备注 |
|:---|:---|:---|
| JAVA_HOME | C:\Software\Java\jdk1.8.0_152 | 设置 JAVA 路径，JAVA_HOME 为变量 |
| CLASSPATH | %JAVA_HOME%/lib | 设置运行 JAVA 程序时加载的依赖包路径 |
| Path | %JAVA_HOME%\bin; | 这个变量是系统自带的，不要删除其他的变量，追加变量值就好。作用：**添加 JAVA 运行脚本到配置中，有了这个配置就可以直接在命令行运行 java 相关命令** |


## 验证

通过在命令行中敲下 java 并回车，看到如下效果就是安装成功。

![04successjpg](http://www.liebrother.com/upload/46771b4981234cb58ec84b4c81f6f73f_04success.jpg) 

Java 教程系列持续更新ing，欢迎关注公众号：**LieBrother**，第一时间获取文章推送。

<center>

![公众号](http://www.liebrother.com/upload/df81ac224abe46b38131a0e78f4dcf9c_wechat.jpg)

</center>