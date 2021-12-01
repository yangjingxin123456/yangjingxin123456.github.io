---
permalink: /
title: "欢迎来到超级懒的小周的自留地/学术废弃站？"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/zhoulvbang/zhoulvbang.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/zhoulvbang/zhoulvbang.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

这是由 [academicpages template](https://github.com/zhoulvbang/zhoulvbang.github.io) 提供支持并托管在 GitHub 页面上的网站的首页。 [GitHub pages](https://pages.github.com) 是一项免费服务，在该服务中，网站是根据存储在 GitHub 存储库中的代码和数据构建和托管的，当对存储库进行新提交时会自动更新。这个模板是从 Michael Rose 创建的 [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) 衍生出来的，然后扩展到支持学术界拥有的各种内容：出版物、演讲、教学、作品集、博客文章和动态生成的简历。现在就可以fork[this repository](https://github.com/zhoulvbang/zhoulvbang.github.io)，修改配置和markdown文件，添加自己的PDF等内容，免费拥有自己的站点，没有广告！这个模板的旧版本支持我自己的个人网站 [stuartgeiger.com](http://stuartgeiger.com)，它使用 [this Github repository](https://github.com/staeiou/staeiou.github.io )

A data-driven personal website：一个数据驱动的个人网站
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

与许多其他基于 Jekyll 的 GitHub Pages 模板一样，academicpages 使您可以将网站的内容与其形式分开。 您网站的内容和元数据在结构化的 Markdown 文件中，而其他各种文件构成主题，指定如何将该内容和元数据转换为 HTML 页面。 您将这些各种 Markdown (.md)、YAML (.yml)、HTML 和 CSS 文件保存在公共 GitHub 存储库中。 每次提交并向存储库推送更新时，[GitHub pages](https://pages.github.com/) 服务会根据这些文件创建静态 HTML 页面，这些页面免费托管在 GitHub 的服务器上。

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://zhoulvbang.github.io/talkmap.html).

动态内容管理系统（如 Wordpress）的许多功能都可以通过这种方式实现，使用一小部分计算资源，并且对黑客和 DDoSing 的脆弱性要小得多。 您还可以将主题修改为您喜欢的内容，而无需触及您网站的内容。 如果你在 Jekyll/HTML/CSS 中损坏了一些无法修复的东西，那么描述你的演讲、出版物等的 Markdown 文件是安全的。 您可以回滚更改，甚至删除存储库并重新开始——只需确保保存markdown文件！ 最后，您还可以编写处理站点上结构化数据的脚本，例如分析元数据的[this one](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.ipynb) 在有关演讲的页面中显示[a map of every location you've given a talk](https://zhoulvbang.github.io/talkmap.html)。

Getting started：入门
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)：如果您没有，请注册一个 GitHub 帐户并确认您的电子邮件（必需！）
1. Fork [this repository](https://github.com/zhoulvbang/zhoulvbang.github.io) by clicking the "fork" button in the top right. ：通过单击右上角的"fork"按钮fork [this repository](https://github.com/zhoulvbang/zhoulvbang.github.io)。
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.：转到存储库的设置（以"Code"开头的选项卡中最右侧的项目应位于"Unwatch"下方）。 将存储库重命名为“[您的 GitHub 用户名].github.io”，这也将是您网站的 URL。
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")：设置站点范围的配置并创建内容和元数据（见下文——另见 [this set of diffs](http://archive.is/3TPas) 显示哪些文件被更改以设置 [an example site](https: //getorg-testacct.github.io) 对于用户名为“getorg-testacct”的用户）
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf. ：将任何文件（如 PDF、.zip 文件等）上传到 files/ 目录。它们将出现在 https://[您的 GitHub 用户名].github.io/files/example.pdf。
1. Check status by going to the repository settings, in the "GitHub pages" section：通过转到“GitHub 页面”部分中的存储库设置来检查状态

Site-wide configuration：全站配置
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

该站点的主要配置文件位于 [_config.yml](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/_config.yml) 的基目录中，它定义了 侧边栏和其他站点范围的功能。 您需要将默认变量替换为关于您自己和您站点的 github 存储库的变量。 顶部菜单的配置文件在[_data/navigation.yml](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/_data/navigation.yml)。 例如，如果您没有作品集或博客文章，您可以从该 navigation.yml 文件中删除这些项目以将它们从标题中删除。

Create content & metadata：创建内容和元数据
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/zhoulvbang/zhoulvbang.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://zhoulvbang.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://zhoulvbang.github.io/talkmap.html) (if you run this [python file](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

对于站点内容，每种类型的内容都有一个 Markdown 文件，这些文件存储在 _publications、_talks、_posts、_teaching 或 _pages 等目录中。例如，每个talk都是[_talks directory](https://github.com/zhoulvbang/zhoulvbang.github.io/tree/master/_talks)中的一个markdown文件。在每个 Markdown 文件的顶部是 YAML 中关于谈话的结构化数据，主题将解析这些数据以做很多很酷的事情。在[Talks page](https://zhoulvbang.github.io/talks)上，使用相同的结构化数据生成演讲列表，每个[individual page](https://zhoulvbang.github.io /talks/2012-03-01-talk-1) 用于具体的谈话，[简历页面](https://zhoulvbang.github.io/cv) 的谈话部分，以及[map of places you've given a talk](https://zhoulvbang.github.io/talkmap.html)（如果你运行这个 [python file](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap. py) 或 [Jupyter notebook](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.ipynb)，它根据 _talks 目录的内容为地图创建 HTML）。

配置私有域名
------
由于网络问题，大陆地区一般是难以访问[GitHub](https://github.com/)，为了让自己的主页/网站可以被访问，我们可以配置一个私有域名，域名可以自行前去[腾讯云](https://console.cloud.tencent.com/)和[阿里云](https://cn.aliyun.com/)购买，购买之后等待其确认，然后解析这个域名，将上述域名(及www域名)解析到[yourname].github.io的IP地址，主机地址是GitHub的主机地址，一般有两个，分别是 `192.30.252.153`、`192.30.252.154`，将其解析好后，转到GitHub界面，直接在`github.io`仓库的`Settings`的`GitHub Pages`项直接设置`Custom domain`，GitHub会自动添加`CNAME`文件，你可以选择在`Custom domain`中直接输入你的域名`www.xxx.cn`或者在`CNAME`文件中进行修改，将你的域名输入，保存。然后刷新~

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/zhoulvbang/zhoulvbang.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

我还创建了 [a set of Jupyter notebooks](https://github.com/zhoulvbang/zhoulvbang.github.io/tree/master/markdown_generator
) 将包含有关演讲或演示的结构化数据的 CSV 转换为单独的 Markdown 文件，这些文件将针对学术页面模板进行正确格式化。 该目录中的示例 CSV 是我用来在 stuartgeiger.com 上创建自己的个人网站的那些。 我通常的工作流程是，我保留一份我的出版物和演讲的电子表格，然后在这些笔记本中运行代码以生成markdown文件，然后提交并将它们推送到 GitHub 存储库。

How to edit your site's GitHub repository：如何编辑站点的 GitHub 存储库
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

许多人使用 git 客户端在他们的本地计算机上创建文件，然后将它们推送到 GitHub 的服务器。 如果你对git不熟悉，可以直接在github.com界面直接编辑这些配置和markdown文件。 导航到一个文件:如 [this one](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/_talks/2012-03-01-talk-1.md)并单击铅笔图标 在内容预览的右上角("Raw  Blame  History"按钮右侧)。您可以通过单击铅笔图标右侧的垃圾桶图标来删除文件。您也可以创建新文件或上传 通过导航到目录并单击“创建新文件”或“上传文件”按钮来创建文件。

Example: editing a markdown file for a talk:示例：为演讲编辑 Markdown 文件
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info:欲了解更多信息
------
More info about configuring academicpages can be found in [the guide](https://zhoulvbang.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

有关配置学术页面的更多信息可以在 [the guide](https://zhoulvbang.github.io/markdown/) 中找到。 [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)（这个主题是从它派生出来的）也可能会有所帮助。
