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

## fortune  幸运饼干

美国中餐馆的最后一道菜，往往是小甜饼，叫做"幸运饼"（fortune cookie）。里面有一张纸条，写着人生格言。

这种形式的格言，显然很受欢迎。早在1979年，就有人写了一个叫做 fortune 的小程序。在命令行下输入fortune，就会跳出一句。

![](/images/fortune-en.png)

安装： `sudo apt-get install fortune`

安装后它默认的格言库都是英语的，我们可以安装中文库：

```
git clone git@github.com:ruanyf/fortunes.git

sudo mv fortunes/data/* /usr/share/games/fortunes/

```

之后输入`fortune` 就是中文咯！

![](/images/fortune-cn.png)


当然你可以把它合理地添加到zshrc文件中，每次登录终端都会收获一份好心情！