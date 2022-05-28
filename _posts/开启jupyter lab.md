# 开启jupyter lab

## 打开anaconda powershell prompt

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image2.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image2.png)

## 激活base环境

conda activate base

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image3.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image3.png)

anaconda可以创建无数个python环境，每个环境里分别安装不同的包、互相不影响。Base是最基础的环境，你也可以自己创建一个环境。

## 切换为清华源

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/

conda config --set show_channel_urls yes

源是你安装包的库，默认的源速度较慢，改为清华源可以加快下载速度。

## 安装Jupyter lab

Pip install jupyterlab

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image4.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image4.png)

Jupyter lab的安装只需要一行命令，键入后等待下载即可。

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image5.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image5.png)

## 进入jupyter lab

Jupyter lab

键入jupyter lab后，通常会直接跳转至浏览器，打开lab窗口。如若没有，你也可以在浏览器输入[http://localhost:8888/lab](http://localhost:8888/lab)，访问lab实验室。

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image6.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image6.png)

## Jupyter lab

Lab窗口界面如下：

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image7.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image7.png)

最左侧是选项卡，包括工作区、标签、插件中心，左侧栏是工作区的文件夹，你可以切换到你想要保存、运行文件的位置。右侧就是编辑区啦。接下来让我们创建一个notebook文件，享受jupyter便捷的交互吧！

## Notebook文件

Notebook文件是jupyter lab特有的格式，因其可以将代码分块运行、直接在文档中显示、丰富的备注样式，因此很适合用来教学、数据分析。如下图所示，创建一个notebook文件。

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image8.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image8.png)

选择要用的内核。当我们的anaconda中有多个环境时，选择内核可以切换不同的环境，但现在还没这个需求。

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image9.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image9.png)

## 编辑

在notebook中有两种块：code和markdown。

Code块用来写代码，输入python语句后按shift+enter键可以运行结果。

Markdown块用来做注释，不会被执行。

下面对不同的模式进行介绍：

1. 编辑和非编辑
编辑状态下有光标，可以键入字符，白色
非编辑状态下无光标，不可以编辑，灰色
    
    ![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image10.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image10.png)
    
    ![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image11.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image11.png)
    
2. Code块和markdown块
code块的左侧有 [*]
markdown块的左侧空白
两者在非编辑状态下可以通过Y键和M键相互切换
    
    ![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image12.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image12.png)
    
    ![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image13.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image13.png)
    

## Markdown基本语法

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image14.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image14.png)

按下shift+enter键显示格式，效果如图

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image15.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image15.png)

这让你可以方便的在文件中添加注释和说明，然后在互联网上分享

## 代码块

以numpy和matplotlib库为例，简单的说，numpy是用来处理数据的库，在面对大量的数据时，他比excel更快速、自由；matplotlib是用来绘图的库，用来可视化分析结果。

首先，你需要安装这两个库

在anaconda powershell中像安装lab那样

pip install numpy, matplotlib

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image16.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image16.png)

一些绘图基础知识

画板figure，画纸Sublpot画质，可多图绘画

画纸上最上方是标题title，用来给图形起名字

坐标轴Axis,横轴叫x坐标轴label，纵轴叫y坐标轴ylabel

图例Legend 代表图形里的内容

网格Grid，图形中的虚线，True显示网格

点 Markers：表示点的形状。

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image17.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image17.png)

## 绘图基本操作

![%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image18.png](%E5%BC%80%E5%90%AFjupyter%20lab%20a6855421202e4bc6acd565619b24c65d/image18.png)