[课程地址：黑马程序员-IDEA快速使用入门视频](https://www.bilibili.com/video/BV1tW411M7QL)
目录：
- [1.下载及安装](#1%e4%b8%8b%e8%bd%bd%e5%8f%8a%e5%ae%89%e8%a3%85)
  - [1.1下载](#11%e4%b8%8b%e8%bd%bd)
  - [1.2安装](#12%e5%ae%89%e8%a3%85)
  - [1.3破解](#13%e7%a0%b4%e8%a7%a3)
- [2.初始化配置](#2%e5%88%9d%e5%a7%8b%e5%8c%96%e9%85%8d%e7%bd%ae)
  - [2.1使用默认配置](#21%e4%bd%bf%e7%94%a8%e9%bb%98%e8%ae%a4%e9%85%8d%e7%bd%ae)
  - [2.2配置IDEA](#22%e9%85%8d%e7%bd%aeidea)
- [3.基本使用](#3%e5%9f%ba%e6%9c%ac%e4%bd%bf%e7%94%a8)
  - [3.1基本配置](#31%e5%9f%ba%e6%9c%ac%e9%85%8d%e7%bd%ae)
    - [主题设置](#%e4%b8%bb%e9%a2%98%e8%ae%be%e7%bd%ae)
    - [代码字体](#%e4%bb%a3%e7%a0%81%e5%ad%97%e4%bd%93)
    - [控制台字体与颜色](#%e6%8e%a7%e5%88%b6%e5%8f%b0%e5%ad%97%e4%bd%93%e4%b8%8e%e9%a2%9c%e8%89%b2)
    - [字体编码格式](#%e5%ad%97%e4%bd%93%e7%bc%96%e7%a0%81%e6%a0%bc%e5%bc%8f)
    - [鼠标滚轮改变代码字体大小](#%e9%bc%a0%e6%a0%87%e6%bb%9a%e8%bd%ae%e6%94%b9%e5%8f%98%e4%bb%a3%e7%a0%81%e5%ad%97%e4%bd%93%e5%a4%a7%e5%b0%8f)
    - [展示代码行数和方法分割线](#%e5%b1%95%e7%a4%ba%e4%bb%a3%e7%a0%81%e8%a1%8c%e6%95%b0%e5%92%8c%e6%96%b9%e6%b3%95%e5%88%86%e5%89%b2%e7%ba%bf)
    - [代码格式化](#%e4%bb%a3%e7%a0%81%e6%a0%bc%e5%bc%8f%e5%8c%96)
    - [代码提示](#%e4%bb%a3%e7%a0%81%e6%8f%90%e7%a4%ba)
    - [自动导包](#%e8%87%aa%e5%8a%a8%e5%af%bc%e5%8c%85)
    - [文档提示](#%e6%96%87%e6%a1%a3%e6%8f%90%e7%a4%ba)
  - [3.2安装插件](#32%e5%ae%89%e8%a3%85%e6%8f%92%e4%bb%b6)
  - [3.3环境(JDK)配置](#33%e7%8e%af%e5%a2%83jdk%e9%85%8d%e7%bd%ae)
  - [3.4创建JavaSE工程](#34%e5%88%9b%e5%bb%bajavase%e5%b7%a5%e7%a8%8b)
  - [3.5配置JVM参数](#35%e9%85%8d%e7%bd%aejvm%e5%8f%82%e6%95%b0)
  - [3.6Debug](#36debug)
  - [3.7创建javaWeb工程](#37%e5%88%9b%e5%bb%bajavaweb%e5%b7%a5%e7%a8%8b)
      - [创建工程](#%e5%88%9b%e5%bb%ba%e5%b7%a5%e7%a8%8b)
      - [Tomcat](#tomcat)
  - [3.8添加第三方依赖](#38%e6%b7%bb%e5%8a%a0%e7%ac%ac%e4%b8%89%e6%96%b9%e4%be%9d%e8%b5%96)
  - [3.9创建servlet](#39%e5%88%9b%e5%bb%baservlet)
  - [3.10Maven的配置](#310maven%e7%9a%84%e9%85%8d%e7%bd%ae)
  - [3.11创建Maven工程](#311%e5%88%9b%e5%bb%bamaven%e5%b7%a5%e7%a8%8b)
  - [3.12Maven视图介绍](#312maven%e8%a7%86%e5%9b%be%e4%bb%8b%e7%bb%8d)
  - [3.13Maven创建javaWeb工程](#313maven%e5%88%9b%e5%bb%bajavaweb%e5%b7%a5%e7%a8%8b)
  - [3.14Maven创建聚合工程](#314maven%e5%88%9b%e5%bb%ba%e8%81%9a%e5%90%88%e5%b7%a5%e7%a8%8b)
  - [3.15使用SVN管理代码](#315%e4%bd%bf%e7%94%a8svn%e7%ae%a1%e7%90%86%e4%bb%a3%e7%a0%81)
  - [3.16使用Git管理代码](#316%e4%bd%bf%e7%94%a8git%e7%ae%a1%e7%90%86%e4%bb%a3%e7%a0%81)
- [4.常用快捷键](#4%e5%b8%b8%e7%94%a8%e5%bf%ab%e6%8d%b7%e9%94%ae)
# 1.下载及安装

## 1.1下载

开源版（Community）完全免费，旗舰版（Ultimate）需要收费，但是注册账号后可以试用30天

在这里我们直接安装旗舰版（Ultimate）

网盘链接：https://pan.baidu.com/s/1reFzREf5JvAyYwtE9SO5gA 
提取码：hvj5 

## 1.2安装

1. 解压后打开ideaIU-2018.2.2.exe，双击即可

2. 安装位置建议不要放在C盘，文件过大

3. 点击Create Desktop Shortcut，可以创建桌面快捷方式，64-bit表示64位的电脑

   Create Associations下面的选项都不建议选中，比如选中.java后，java文件会默认用idea打开，其实没有必要，用其他软件打开文件时会带来不便

   <img src="https://img-blog.csdnimg.cn/20191022203652688.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 50%;" />

   4. 文件过大，安装需要等待一段时间，安装完成后先不要打开，也不要勾选Run IntelliJ IDEA按钮，先去破解再打开软件

## 1.3破解

1. 解压crack.rar后里面有个JetbrainsCrack.jar

2. 打开安装bin目录，比如我的E:\Program Files\JetBrains\IntelliJ IDEA 2018.2.2\bin

3. 把JetbrainsCrack.jar放到bin目录，其中目录要和你的安装目录保持一致

4. bin目录下找到idea.exe.vmoptions 和 idea64.exe.vmoptions两个文件，以文本格式打开，在两个文件最后一行分别追加新的一行下面的配置，其中目录要和你的安装目录保持一致，JetbrainsCrack.jar和你的破解包名字保持一致，每个人的破解包名称可能不一样，以我的安装目录为例：

   javaagent:E:\Program Files\JetBrains\IntelliJ IDEA 2018.2.2\bin\JetbrainsCrack.jar

5. 启动 IntelliJ IDEA , IDEA在初次运行时会让你选择是否导入设置，如下图所示
   <img src="https://img-blog.csdnimg.cn/2019102220372667.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 67%;" />
   但是初次使用或者没有保存设置的大多要重新设置。

6. 点击`Activation code`会让输入激活码

   <img src="https://img-blog.csdn.net/20180702134912834?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM4MDc1NDI1/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="img" style="zoom:80%;" />

7. 解压的crack的文件夹里面有个readme.txt的文件，用记事本打开找到Enter key，复制下面的激活码输入后点击OK，即可激活成功

8. 当前激活码对2018年的idea安装包版本有效，如果无效，可能是你的idea版本太高，换个较低的版本试试

# 2.初始化配置

## 2.1使用默认配置

如果想要偷懒可以选择直接关掉配置窗口或者点击跳过配置按钮，如下图所示。这样就会直接使用默认配置了。
<img src="https://img-blog.csdnimg.cn/20191022203809735.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 50%;" />

## 2.2配置IDEA

不过IDEA的默认配置会引入大量的插件，不建议大家直接使用，下面将会向大家怎么配置自己的IDEA。

1. 选择UI主题，在IDEA中提供了两种UI主题：Darcula黑色主题，Light白色主题
   <img src="https://img-blog.csdnimg.cn/20191022203836461.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 33%;" />

   大家可以根据自己的喜好选择，后续使用如果不喜欢也可以在设置中进行修改

2. 设置默认插件，这一步需要根据自己的情况选择禁止一些用不上的组件
   <img src="https://img-blog.csdnimg.cn/20191022203918329.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 33%;" />

3. 配置构建工具，这里建议把自己不用的构建工具插件禁用
   <img src="https://img-blog.csdnimg.cn/20191022203957215.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:50%;" />

4. 以我自己使用习惯，只会启用maven（默认是全启用），如下图所示
   <img src="https://img-blog.csdnimg.cn/20191022204025635.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom: 33%;" />

5. 配置版本控制工具，我选择是只使用git和github，大家可以根据自己的使用习惯选择版本控制工具
   <img src="https://img-blog.csdnimg.cn/20191022204110833.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />

6. 配置测试工具，根据需要选择开启
   <img src="https://img-blog.csdnimg.cn/20191022204149945.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />

7. 配置Swing，如果不是开发Swing项目，建议关闭（默认开启），关闭状态如下图所示
   ![在这里插入图片描述](https://img-blog.csdnimg.cn/2019102220421431.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70)

8. 配置Android，同Swing配置，非安卓开发者建议关闭
   ![在这里插入图片描述](https://img-blog.csdnimg.cn/20191022204300167.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70)

9. 配置其他工具，这个一般我不会进行修改
   <img src="https://img-blog.csdnimg.cn/2019102220433688.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />

10. 配置插件开发，非IDEA插件开发者建议关闭
    ![在这里插入图片描述](https://img-blog.csdnimg.cn/20191022204352106.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70)

11. 配置好后的界面，如下图所示
    <img src="https://img-blog.csdnimg.cn/20191022204406657.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />

12. 配置功能插件，这里的插件都需要安装（自动会下载）
    <img src="https://img-blog.csdnimg.cn/20191022204532195.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />
13. 需要注意其实这里有个IDEA官方的教程插件，有兴趣的朋友可以试着安装使用

<img src="https://img-blog.csdnimg.cn/20191022204546304.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:50%;" />

14.然后点击右下角的启动IDEA按钮就可以愉快地使用IDEA了
<img src="https://img-blog.csdnimg.cn/20191022204644608.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ExNTgxMjM=,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:33%;" />

# 3.基本使用

## 3.1基本配置

`File`->`Settings`或者快捷键`Ctrl+Alt+S`

### 主题设置

主题颜色：

`Appearance&Behavior`->`Appearance`->`UI Options`->`Theme`

主题字体：建议选择支持中文的，这个按钮不选中时为系统默认，选中后可以修改

`Appearance&Behavior`->`Appearance`->`UI Options`->`Theme`->`Override default fonts by(not recommend)`

### 代码字体

`Editor`->`Font`

`Show only monospaced fonts`表示使用等宽字体，一般选中

`Size`表示字体大小

`Line spacing`表示行距

### 控制台字体与颜色

字体：

`Editor`->`Color Scheme`->`Console Font`

`Use console font instead of default`选中表示修改默认字体

`Show only monospaced fonts`表示使用等宽字体，一般选中

`Size`表示字体大小

`Line spacing`表示行距

颜色：

`Editor`->`Color Scheme`->`Console Colors`

### 字体编码格式

`Editor`->`File Encodings`

把所有的`GBK`都改为`UTF-8`

### 鼠标滚轮改变代码字体大小

`Editor`->点击`General`

`Mouse`->`Change font size (Zoom) with Ctrl+Mouse Wheel`

### 展示代码行数和方法分割线

`Editor`->`General`->`Appearance`

`show line numbers`：代码行数

`Show method separators`：方法分割线

### 代码格式化

`Editor`->`Code Style`->点击`Java`

`Blank Lines`：`Keep Maximum Blank Lines`下的选项全部改为1，表示行之间的行间隔

### 代码提示

`Editor`->`General`->`Code  Completion`

`Case sensitive completion`选项改为：`None`，表示提示时忽略大小写

### 自动导包

`Editor`->`General`->`Auto  Import`

`Java`->`Insert import on paste`选项改为：`All`，表示不用提示，直接帮我们导包

### 文档提示

`Editor`->`General`

`Other`->`Show quick documentation on mouse move`，选中会有文档提示，`Delay(ms)`表示提示延迟的毫秒数

## 3.2安装插件

`File`->`Settings`或者快捷键`Ctrl+Alt+S`->`Plugins`

`Install JetBrains plugin...`安装idea官方插件

`Browse repositories...`

`Install plugin from disk..`

## 3.3环境(JDK)配置

`File` ->`Project Structure`或者快捷键`Ctrl+Alt+Shift+S`

`Project`->`New`->`JDK`->然后选择`JDK的安装路径即可`

一般我们的电脑配置过`java`的环境变量后，可以找到安装路径

`JDK`的安装路径：`选中计算机`->`右键`->`属性`->`高级系统设置`->`环境变量`->`系统变量`

找到`JAVA_HOME`，`JAVA_HOME`对应的值即为`JDK`的安装路径

## 3.4创建JavaSE工程

`File` ->`New` ->`Project `->`JAVA`

`Project name`表示项目名称

比如：demo

`Project location`表示项目路径

比如：G:\project\demo

**注意：**`Project location`也要包含`Project name`

小知识：

> psvm：创建main方法款快捷键
> sout： System.out.println()快捷键
> 不需要保存，idea会自动保存

## 3.5配置JVM参数

`Help` ->`Edit custom JVM Options...`

下面几个选项参数配置大一点，如下：

```xml
-Xms1024m
-Xmx2048m
-XX:ReservedCodeCacheSize=500m
```

## 3.6Debug

在行号的右侧点击一下即可，和eclipse点两下稍有不同

`F7`逐行断点，调用的方法也会进入

`F8`逐行断点，调用的方法不会进入

`F9`直接跳到下一个断点

## 3.7创建javaWeb工程

#### 创建工程

`File` ->`New` ->`Project `->`JAVA`

要选中`Web Application`

其中点击`JAVA EE`时可以切换JAVA EE的版本，点击`Web Application`时可以切换serverLet版本

`Project name`表示项目名称

比如：demo

`Project location`表示项目路径

比如：G:\project\demo

**注意：**`Project location`也要包含`Project name`

小知识：

>  设置idea是否打开上次的工程：	
>
> `Appearance&Behavior`->`System Settings`->`Reopen last project on starup`

#### Tomcat

`Add Configuration...`->`+`->`34 items more(irrelevant)...`->`Tomcat Server`->`Local`

`Application Server`指定server环境，点右面的`Configure...`

`Tomcat home`指定本地tomcat安装路径

`Deployment`可以增减项目 

`After launch`表示server后是否直接用浏览器打开项目

`On Update action`选择`Redeploy`表示修改资源后马上同步更新

**404问题解决方案：**

参考链接：http://www.mamicode.com/info-detail-2204130.html

将Tomcat的首页的工程部署到Tomcat服务器上，部署步骤如下：

选择菜单栏“Run-->Edit Configuration...-->Deployment”,选择右上角绿色“+”，选择“External Source...”，将Apache-tomcat的webapps目录下的ROOT文件夹选中，点击OK，及完成Tomcat的首页的工程的部署。选择ROOT文件后右侧Application Context 可不填写，默认即可。

<img src="http://image.mamicode.com/info/201802/20180227154719133316.png" alt="技术分享图片" style="zoom: 33%;" />

<img src="http://image.mamicode.com/info/201802/20180227154719206561.png" alt="技术分享图片" style="zoom:50%;" />

 

 选择菜单栏“Run-->Edit Configuration...-->Deployment”,选择右上角绿色“+”，选择“Artifact...”，选择exploded项，点击OK。

 <img src="http://image.mamicode.com/info/201802/20180227154719257344.png" alt="技术分享图片" style="zoom: 50%;" /> 

 右侧Application Context 可填写为访问URL名称，也可以写成/表示默认访问项目

<img src="http://image.mamicode.com/info/201802/20180227154719298361.png" alt="技术分享图片" style="zoom:33%;" />

再次运行项目，项目成功运行啦。

这次再访问http://localhost:8080/，熟悉的猫咪出来了。

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

![技术分享图片](http://image.mamicode.com/info/201802/20180227154719377466.png)

2.将tomcat中的catalina.bat打开，如果之前设置了set JAVA_POST,去掉，就OK了，这里的原因是因为Idea会给tomcat配置参数，如果之前有，就会覆盖IDea的，导致冲突

[Idea配置tomcat运行成功后报404](http://www.mamicode.com/info-detail-2204130.html)

标签：[绿色](http://www.mamicode.com/so/1/绿色)  [cal](http://www.mamicode.com/so/1/cal)  [名称](http://www.mamicode.com/so/1/名称)  [ext](http://www.mamicode.com/so/1/ext)  [图片](http://www.mamicode.com/so/1/图片)  [步骤](http://www.mamicode.com/so/1/步骤)  [ati](http://www.mamicode.com/so/1/ati)  [host](http://www.mamicode.com/so/1/host)  [技术分享](http://www.mamicode.com/so/1/技术分享)  

原文地址：https://www.cnblogs.com/jbml-154312/p/8479030.html

## 3.8添加第三方依赖

选中`WEB-INF`文件夹，右键`New`一个`Directory`：lib

选中lib后，`File`->`Project Structure(Ctrl+Alt+Shift+S)`或者直接点击菜单栏上的`Project Structure`按钮	

然后点击`Libraries`,再点击`+`加号，选择Java，找到刚刚创建的`lib`文件夹，然后在Modules里的`Dependencies`再选中`lib`即可，最后点击ok.

## 3.9创建servlet

src下包里直接`New`一个servlet即可，创建完成后发现会报错，需要添加Tomcat依赖

选中项目后，`File`->`Project Structure(Ctrl+Alt+Shift+S)`或者直接点击菜单栏上的`Project Structure`按钮，在Modules里的`Dependencies`点右面`+`加号，选择`Library`选项，再选`Java`，选择出来后的Tomcat，点击`Add Selected`，再选中Tomcat，点击`Apply`和`OK`即可

> servlet代码事例：

```java
//doPost方法里代码
response.getWriter().write("hello servlet");
//doGet方法里代码
doPost(request,response);
```

> servlet配置(web.xml)

```xml
<servlet>
    <servlet-name>HelloServlet</servlet-name>
    <servlet-class>com.itheima.web.HelloServlet</servlet-class>
</servlet>
<servlet-mapping>
    <servlet-name>HelloServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
</servlet-mapping>
```

重启Tomcat访问：http://localhost:8080/hello

## 3.10Maven的配置

`File`->`Settings`或者快捷键`Ctrl+Alt+S`->`Build,Execution,Deployment`->`Build Tools`->`Maven`

`Maven home dircetory`：表示maven安装路径

`User settings file`：表示maven仓库设置

`Local repository`：表示maven本地仓库位置

`Override`：表示覆盖默认配置，改为本地配置

## 3.11创建Maven工程

`File`->`New`->`Project`->``Maven``

选中`Create from archeype`：表示从模板原型创建项目

找到`org.apache.maven.archetypes:maven-archetype-quickstart`，点击Next

```java
输入groupId和artifactId，比如：
groupId：com.itheima.maven
artifactId：idea_javase_maven
```

然后选择对应的maven

## 3.12Maven视图介绍

右面`Maven Projects`可执行一些maven操作

参考链接：https://www.jianshu.com/p/942be26a03e0

<img src="https://img2018.cnblogs.com/blog/1242944/201906/1242944-20190629175705462-531469084.png" alt="img" style="zoom:67%;" />

参考链接：https://www.jianshu.com/p/942be26a03e0

<img src="https://upload-images.jianshu.io/upload_images/2495229-5d3f62d2d7a789a2.png?imageMogr2/auto-orient/strip|imageView2/2/w/443/format/webp" alt="img" style="zoom:67%;" />

工具栏按钮的作用

参考链接：https://blog.csdn.net/qq_22515647/article/details/82142399

<img src="https://img-blog.csdn.net/20180828092827104?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzIyNTE1NjQ3/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="img" style="zoom: 67%;" />

1.Execute Maven Goal  弹出可执行的 Maven 命令的输入框。有些情况下我们需要通过书写某些执行命令来构建项目，就可以通过此按钮

2.Toggle Offline Mode 英文释义 https://blog.csdn.net/tanga842428/article/details/53206783?locationNum=10&fps=1(大概就是把maven 的网络关闭,必须使用本地资源)

3.toggle "skip test" mode 不但跳过单元测试的运行，也跳过测试代码的编译。

4.Show Dependencies 显示项目依赖的结构图，可以方便我们直观项目的依赖包情况。https://blog.csdn.net/qq_27093465/article/details/69226949

5.collapse all 收起所有

<img src="https://img-blog.csdnimg.cn/20190528003938594.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQwNjczNzg2,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述" style="zoom:67%;" />

## 3.13Maven创建javaWeb工程

`File`->`New`->`Project`->``Maven``

选中`Create from archeype`：表示从模板原型创建项目

找到`org.apache.maven.archetypes:maven-archetype-webapp`，点击Next

```java
输入groupId和artifactId，比如：
groupId：com.itheima.maven
artifactId：idea_javase_maven
```

然后选择对应的maven

在src/main下分别创建java和resources文件夹

分别选中创建的文件夹，右键后点击`Mark Directory as`分别对应`Sources Root`和`ReSources Root`

>  **在`pom.xml`里增加Tomcat插件**
>
> <plugin>在<build>里的<plugins>里
>
> 注意不是写在<pluginManagement>里，写到这里会找不到插件

```
<!--Tomcat插件-->
<plugin>
  <groupId>org.apache.tomcat.maven</groupId>
  <artifactId>tomcat7-maven-plugin</artifactId>
  <version>2.2</version>
  <configuration>
      <port>9999</port>
      <path>/</path>
  </configuration>
</plugin>
```

然后去右面的`Maven Projects`视图里

找到项项目里的`Plugins`的`tomcat7`，点击`tomcat7`里的`tomcat7:run`即可启动项目

也可以用命令的方式在`Execute Maven Goal`按钮进行启动`tomcat7:run`

## 3.14Maven创建聚合工程

1. 先创建父工程：idea_mall

   ```
   idea_mall
   idea_portal
   idea_back
   ```

   `File`->`New`->`Project`->``Maven``

   选中`Create from archeype`：表示从模板原型创建项目

   找到`org.apache.maven.archetypes:maven-archetype-site`，点击Next

   ```java
   输入groupId和artifactId，比如：
   groupId：com.itheima
   artifactId：idea_mall
   ```

2. 为idea_mall创建子模块：idea_portal

   ```
   idea_portal
   
   	idea_portal_dao
   
   	idea_portal_service
   
   	idea_portal_web
   ```

   在idea_mall项目增加一个idea_portal项目

   选中idea_mall然后右键->`New`->`Module`

   找到`org.apache.maven.archetypes:maven-archetype-site`，点击Next

   ```java
   输入groupId和artifactId，比如：
   groupId：com.itheima
   artifactId：idea_portal
   ```

   在最后一步时`Content root`和`Module file location`

   保持idea_portal和idea_mall同级，不要放在idea_mall路径的下面

3. 为idea_portal创建子模块：idea_portal_dao

   在idea_portal项目增加一个idea_portal_dao模块

   选中idea_portal然后右键->`New`->`Module`

   找到`org.apache.maven.archetypes:maven-archetype-quickstart`，点击Next

   ```java
   输入groupId和artifactId，比如：
   groupId：com.itheima
   artifactId：idea_portal_dao
   ```

   在最后一步时`Content root`和`Module file location`

   保持idea_portal_dao为idea_portal下级，放在idea_portal路径的下面

4. 在idea_portal项目增加一个idea_portal_service模块

   选中idea_portal然后右键->`New`->`Module`

   找到`org.apache.maven.archetypes:maven-archetype-quickstart`，点击Next

   ```java
   输入groupId和artifactId，比如：
   groupId：com.itheima
   artifactId：idea_portal_service
   ```

   在最后一步时`Content root`和`Module file location`

   保持idea_portal_service为idea_portal下级，放在idea_portal路径的下面

   为idea_portal_service添加依赖，依赖idea_portal_service层

   ```xml
   <dependency>
       <groupId>com.itheima</groupId>
       <artifactId>idea_portal_service</artifactId>
       <version>1.0-SNAPSHOT</version>
   </dependency>
   ```

5. 在idea_portal项目增加一个idea_portal_web模块

   选中idea_portal然后右键->`New`->`Module`

   找到`org.apache.maven.archetypes:maven-archetype-webapp`，点击Next

   ```java
   输入groupId和artifactId，比如：
   groupId：com.itheima
   artifactId：idea_portal_web
   ```

   在最后一步时`Content root`和`Module file location`

   保持idea_portal_web为idea_portal下级，放在idea_portal路径的下面

   为idea_portal_web添加依赖，依赖idea_portal_dao层

   ```xml
   <dependency>
       <groupId>com.itheima</groupId>
       <artifactId>idea_portal_dao</artifactId>
       <version>1.0-SNAPSHOT</version>
   </dependency>
   ```

   

6. 同样的创建idea_back子模块

   ```
   idea_back
   
   	idea_back_dao
   
   	idea_back_service
   
   	idea_back_web
   ```

## 3.15使用SVN管理代码

## 3.16使用Git管理代码

1. 开启版本控制

   点击菜单栏`VCS`，选择`Enable Version Contral Integration`，再选择`Git`

2. 设置忽略项

   `File`->`Settings`->`Version Contral`->`Ignored Files`

   点击加号，`Ignore specified file`忽略文件，如：idea_javaWeb_maven.iml文件

   点击加号，`Ignore all files under`忽略文件夹，如：.idea文件夹

3. 上传项目到本地仓库

   点击菜单栏`VCS`，选择`Commit`

4. 上传项目到远程仓库

   点击菜单栏`VCS`，选择`Git`,点击`Push`即可

# 4.常用快捷键

Ctrl+Z：撤销

Ctrl+Shift+Z：重做

Ctrl+X：剪贴

Ctrl+C：复制

Ctrl+V：粘贴

Ctrl+Y：删除当前行

Ctrl+D:复制当前行

Ctrl+Shift+J：将选中的行合并成一行

Ctrl+N：查找类文件

Ctrl+Shift+N：查找文件

Ctrl+G：定位到文件某一行

Alt+向左箭头：返回上次光标位置

Alt+向右箭头：返回至后一次光标位置

Ctrl+Shift+Backspace：返回上次编辑位置

Ctrl+Shift+反斜杠：返回后一次编辑位置

Ctrl+B：定位至变量定义的位置

Ctrl+Alt+B：定位至选中类或者方法的具体实现

Ctrl+Shift+B:直接定位至光标所在变量的类型定义

Ctrl+U：直接定位至当前方法override或者implements的方法定义处

Ctrl+F12：显示当前文件的文件结构

Ctrl+Alt+F12：显示当前文件的路径，并可以方便的将相关父路径打开

Ctrl+H：显示当前类的继承层次

Ctrl+Shift+H：显示当前方法的继承层次

Ctrl+Alt+H：显示当前方法的调用层次

F2：定位至下一个错误处

Shift+F2：定位至前一个错误处

Ctrl+Alt+向上箭头：查找前一个变量共现的地方

Ctrl+Alt+向下箭头：查找下一个变量共现的地方

Ctrl+=：展开代码

Ctrl+-：收缩代码

Ctrl+Alt+=：递归展开代码

Ctrl+Alt+-：递归收缩代码

Ctrl+Shift+=：展开所有代码

Ctrl+Shift+-：收缩所有代码

Ctrl+Shitft+向下箭头：将光标所在的代码块向下整体移动

Ctrl+Shift+向上箭头：将光标所在的代码块向上整体移动

Ctrl+Alt+Shift+向左箭头：将元素向左移动

Ctrl+Alt+Shift+向右箭头：将元素向右移动

Alt+Shift+向下箭头：将行向下移动

Alt+Shift+向上箭头：将行向上移动

Ctrl+F：在当前文件中查找

Ctrl+R：替换字符串

Ctrl+Shift+F:在全局文件中查找字符串

Ctrl+Shift+R：在全局中替换字符串

Alt+F7：查找当前变量的使用，并列表显示

Ctrl+Alt+F7：查找当前变量的使用，并直接对话框提示

Ctrl+F7：在文件中查找符号的使用

Ctrl+Shift+F7：在文件中高亮显示变量的使用

Ctrl+O：重写基类方法

Ctrl+I：实现基类或接口中的方法

Alt+Insert：产生构造方法，get/set方法等

Ctrl+Alt+T：将选中的代码使用if，while，try/catch等包装

Ctrl+Shitf+Delete：去除相关的包装代码

Alt+/：自动完成

Alt+Enter：自动提示完成，抛出异常

Ctrl+J：插入Live Template 快速插入一行或者多行代码

Ctrl+Alt+J：使用Live Template包装

Ctrl+/：使用//注释

Ctrl+Shift+/：使用/\**/注释

Ctrl+Alt+L：格式化代码

Ctrl+Alt+I：自动缩进行

Ctrl+Alt+O：优化import

Ctrl+]：快速跳转至诸如{}围起来的代码块的结尾处

Ctrl+[：快速跳转至诸如{}围起来的代码块的开头处

Ctrl+Shift+Enter：将输入的if，for，函数等等补上{}或者；使代码语句完整

Shift+Enter：在当前行的下方开始新行

Ctrl+Alt+Enter：在当前行的上方插入新行

Ctrl+Delete：删除光标所在至单词结尾处的所有字符

Ctrl+Backspace：删除光标所在至单词开头处的所有字符

Ctrl+向左箭头：将光标移至前一个单词

Ctrl+向右箭头：将光标移至后一个单词

Ctrl+向上箭头：向上滚动一行

Ctrl+向下箭头：向下滚动一行

Ctrl+W：选中整个单词

Ctrl+Shift+U：切换大小写

Shift+F6：重命名

Ctrl+F6：更改函数签名

Ctrl+Shift+F6：更改类型