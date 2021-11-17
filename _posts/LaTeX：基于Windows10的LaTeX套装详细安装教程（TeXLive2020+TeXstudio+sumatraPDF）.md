---
title: 'LaTeX：基于Windows10的LaTeX套装详细安装教程'
date: 2021-11-17
permalink: /posts/2021/11/LaTeX：基于Windows10的LaTeX套装详细安装教程/
tags:
  - cool posts
  - category1
  - category2
---

Headings are cool
======

You can have many headings
======

Aren't headings cool?
------
 
 **1. 前言**

此文写于小美赛（APMCM）前几天，今天latexstudio发布了APMCM的LaTeX写作模板，模板要求使用TeXLive2020进行编译，这让我想继续使用TeXLive2019继续混的想法破灭。

事实上2019还能用，不过我也的确该换了，2020是4月份发布的，但是我才接触LaTeX不久，前辈说先不急着安装新的版本，新版本在发行早期容易出问题，所以就一直放着没管，在后面的时间里面，自己不断地学习，也算是略有心得，期间受到了很多前辈的指点，自己也不停地看了很多的书，所以很多东西都是可以随着自己的想法来

在刚开始学LaTeX的时候，我的文件总是编译不出来，当时那叫一个急啊，一度认为自己的电脑有问题，为了使用TeXLive2019，我前后总共安装了4/5次吧，自己的系统也在初期因此重装了，然后帮朋友和同学也安装了好几次，慢慢的总算稳定下来，然后就开始好好学习了.JPG。
      
絮絮叨叨这么多一方面是发发自己的牢骚，一方面则是希望减少你对LaTeX的陌生感与面对一个新事物而产生的对未知事物的不安与恐惧。

LaTeX对于理工科专业有较好的应用场景，近些年在文科中的应用也逐渐多了起来，在某些时间点上他的主要应用场景就是各项数学建模比赛和软件比赛。
LaTeX广泛应用于学术报告、Paper、学术beamer的撰写和制作，熟练地掌握LaTeX是在学术界生存的必备基本技能之一。
      

 **2. 警告**
 TeXLive升级比较麻烦，一般建议卸载重装，一定要在装之前把程序卸载干净，包括TeXLive和TeXStudio，卸载后清空回收站

 **3. 准备-程序准备**
 这里给出几个渠道下载文件
 

 1. TeXLive
 [清华镜像](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/)这个在网络良好环境下，速度可以
[TeX Live](http://tug.org/texlive/)官方网站
[LaTeXStudio网站](https://latexstudio.net/archives/51801.html)推荐使用
[MiKTeX](https://miktex.org/)
[MacTeX](http://tug.org/mactex/)
对于TeXLive、MiKTeX、MacTeX,以上套装只需安装一个即可，严禁不同套装或不同版本混用。

> 跨平台支撑：MiKTeX 逐步开始支撑 Linux，Mac 平台了。从使用者角度看，TeXLive 是多数国外期刊采用的编译套装，推荐使用。
> MiKTeX 封装套装：MiKTeX 还有封装的版本，比如 proTeXt 是封装了 MikTeX 并把 TeXStudio
> 作为前端编辑器。CTeX 封装了 MikTeX，集成了编辑器 WinEdt 和PostScript 处理软件 Ghostscript 和GSview 等主要工具。CTeX的使用：如果是国内的某些老期刊的话，CTeX 可作为备选版本，待国内老的模板更新上来了，CTeX也完成其使命了。
> 新人安装建议：新手安装的时候，最好下载 full，complete 版本，国内镜像站点不稳定，防止出现缺少常用宏包引入的错误。

 2. TeXstudio
 [啸行大神给的一个路径](https://d.serctl.com/)一定要先看**如何下载教程**
 [老版本百度云](https://pan.baidu.com/s/1m4-Z8fagJUxkw0ghz-0sDA)密码：im38
 [较新版本的百度云](https://pan.baidu.com/s/1S6xpWcX3yhLFEWpiDr2D8g)密码：afgw
 这个在官网下可能受限于国内的网速，而且就我接触的较新版本的texstudio经常在编译时闪退，建议用老一点的版本。
 

> 编辑器用于编写代码的部分，提供了可视化的编辑界面，同时提供方便的工具和编译按钮等。对于初学者界面的辅助按钮和字符提示有一定的学习促进作用。常用的编辑有如下：
> 
> WinEdt - 收费软件，推荐购买后使用，对初学者界面友好。
> 
> TeXworks -常见的 TeX 套装都自带这款编辑器，界面比较清爽，支持代码和 pdf 查看，左右分屏显示。
> 
> TeXStudio （本站下载）- 开源免费的编辑器，界面集成度好。其源于：TeXmaker - 开源免费的编辑器。
> 
> TeXShop (Mac 版) - MacTeX 自带的编辑器，界面比较简洁，与 TeXworks 功能接近。
> 
> TeXPad (Mac 版) - Mac OS 平台下的收费编辑器。

 3. Sumatra-PDF
[sumatra-pdf](https://sumatra-pdf.en.softonic.com/?ex=CORE-139.6)

> Windows下推荐 SumatraPdf 阅读器，这是 Krzysztof Kowalczyk 所开发的轻量级 PDF 阅读器，有安装版和携带版，支持32位和64位系统，同时还提供源码下载。 软件支持异步写入 PDF 文件，对于 LaTeX 使用过程中，一边查看 pdf 一边编译的应用场景，毫无压力，另外，软件文件小，打开 PDF 速度快。
> mac 下的 pdf 阅读器 skim，https://skim-app.sourceforge.io 支持实时更新 pdf 和 synctex

 4. Overleaf

>  在线LaTeX平台（协作平台，无需安装，随时取用） Overleaf：支持多人协作，与 sharelatex
> 进行整合更易用。需要较好网络件,建议使用**Google Chrome**

这里有一个安装顺序，分别是TexLive，然后Sumatra PDF，最后是TeXstudio
 

 **4. Begin TeXLive**
第一，你需要一个TeXLive2020的iso光盘映像文件或者安装包，这里推荐iso光盘映像文件。理由是iso安装非常方便非常方便，看到这里选中iso右键，第一个选项就是“**装载**”
![iso文件](https://img-blog.csdnimg.cn/20201123230751651.png#pic_center)
装载后你会得到一个虚拟光驱![虚拟光驱](https://img-blog.csdnimg.cn/20201123231145917.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
点击**install-tl-windows.bat**，安装开始，欢迎进入漫长的安装时间

![初始化](https://img-blog.csdnimg.cn/20201123235330143.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
这是初始化界面，稍等一会
![welcome](https://img-blog.csdnimg.cn/20201123235436451.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
准备工作，建议点击**Advanced**，得到如下界面
![配置](https://img-blog.csdnimg.cn/20201123235330136.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
在这里修改**TEXDIR**和**N. of collections：Customize**
装在C盘（固态盘）在安装的时候速度会比较快（今天试了一下只用了一个小时不到，但是机械盘可能会需要2-3小时），如果你固态盘空间充裕的话可以考虑安装在这里。

第二个是Customize，这里有很多语言选项，个人建议你可取消掉一些语言包的安装，见下图，像French、German、Japanese、Spanish等我们用不到的语言![语言选项](https://img-blog.csdnimg.cn/20201124000316376.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
点击确定，进入安装，得到如下窗口，蔚为壮观，哈哈哈哈嗝
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020112323533085.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
安装成功过后得到如下界面：**欢迎进入 TeX Live 的世界**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201124000514781.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
这个时候你还需要一个命令行来检验是否安装成功
打开**cmd**，输入**tex v**，得到如下，出现就代表安装成功了![在这里插入图片描述](https://img-blog.csdnimg.cn/20201124000705975.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
![贼可爱](https://img-blog.csdnimg.cn/20201124000845390.jpg#pic_center)

 **5. Begin TeXstudio**

接下安装TeXstudio，安装路径自选，安装好之后打开TeXstudio
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020112400114084.png#pic_center)
选择**options**
再点击**commands**
编辑配置，如果系统给你默认配置好了你就不用管，没有的话你就要自己选一下，可以参考我这个来选择
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201124001457571.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
你也可以在**general**里面选择**Language**和**Style**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201124001530714.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)
打开一个文件，比如说APMCM2020的论文模板，点击编译（**双绿箭头**），如果编译后没有PDF显示可以点击一下那个**放大镜**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201124001757952.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pob3VsdmJhbmc=,size_16,color_FFFFFF,t_70#pic_center)

 **6. 最后**
好的工具的确会提高你的生产力，所以我希望你能从我这里得到帮助，LaTeX在一般的教学中都用不到，它的门槛相较于Word而言，实在是太高了，所以这个程序也只流行在一些高校或者出版集团之中，然后就是像我一样打数模比赛的人。
如果还有不懂的地方欢迎给我留言或者私信，我会尽量及时回复。同时如果你觉得我写的不错，那么欢迎你**点赞**。
最后如果你对LaTeX感兴趣，欢迎你加入组织，一起学习LaTeX。

> 640633524（LaTeX官方交流群）

注释：引用部分均来自LaTeX工作室网站
