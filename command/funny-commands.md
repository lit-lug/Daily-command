有趣的Linux终端命令
===

助大家摆脱对Linux终端的刻板映象

## 前言

Linux终端不仅仅是用来管理系统和来发工作的交互界面，它还可以用来做很多有趣的事情，一起来探索一下吧！

这些有趣的命令很多不会附带在众多发行版中，需要我们自己安装，基于Ubuntu的发行版请注意，请启用universe仓库，因为很多命令不在主仓库中。

##  sl 在终端开火车

`sl` 命令可以在终端运行一辆火车

![](/images/sl.gif)

``` shell 
#安装
sudo apt-get install sl

#使用
sl

#起飞
sl -F
```


## cmatrix   代码雨

`cmatrix` 可以在终端里面掉落各种字符，类似于电影黑客帝国中的标志形象。


![](/images/cmatrix.gif)

```
# 安装
sudo apt-get install cmatrix

#使用
cmatrix

#终止
# 按下Ctrl + C
```