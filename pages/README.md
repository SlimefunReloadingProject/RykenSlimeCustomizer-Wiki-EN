# 主页 :id=home

## 前言

相信你或多或少的听说了一个自定义粘液附属SlimeCustomizer。但是它的局限性太大了。\
为此，我们开发了一个自定义粘液附属插件(RykenSlimeCustomizer)，且比SlimeCustomizer有更多自定义性。
如果你学过Java、JavaScript等这类语言，你就能很快上手写更高级的机器。

欢迎加入QQ群交流：[811756705 (Slimefun Reloading... Project)](https://qm.qq.com/cgi-bin/qm/qr?k=idCPgpiN5wGQwc5fcO4PPLW4UkjAmsKP)

请在使用本附属前详细地阅读《使用前声明》。

## 简介

首先，你一定非常好奇什么是Ryken自定义粘液附属（RykenSlimeCustomizer），他和自定义附属（SlimeCustomizer）又有什么不同？

本页将说明RykenSlimeCustomizer与SlimeCustomizer的优缺点，并解决一部分对于此插件最基础的疑惑

## SlimeCustomizer与RykenSlimeCustomizer

为了更好地展示 SlimeCustomizer 与 RykenSlimeCustomizer 的区别，我们特别写了另外一篇文章，因为 RykenSlimeCustomizer 的优点实在太多了！

[SlimeCustomizer与RykenSlimeCustomizer的区别](plugin/comparison.md)

### SlimeCustomizer 自定义粘液附属

[SlimeCustomizer](https://github.com/SlimefunGuguProject/SlimeCustomizer) 适合新手入门使用，无需学Java等语言，仅通过最基础的配置修改，就能做出基础的附属

SlimeCustomizer通俗易懂，更加简单明了，但是局限性较大，你只能在一个**固定的框架**中自定义

比如：对于机器，你只能安排两个输入和两个输出，所有的机器都是一个统一的格式与菜单

而Ryken自定义粘液附属则支持功能更加丰富的机器自定义，且局限性非常小

以下将讲解Ryken自定义粘液附属

### RykenSlimeCustomizer Ryken粘液自定义附属

RykenSlimeCustomizer将配置与脚本结合（脚本是非必须选项），使自定义的局限性大幅度缩小

你可以通过Ryken粘液自定义附属的脚本功能自定义任何你想要自定义的道具

脚本功能需要编写者有一定的Java基础，但是对于没Java基础的编写者也不用担心

本wiki将列出多个脚本模板，你可以在wiki给出的模板上稍作修改来实现自定义道具物品、高级机器等内容

## 特别说明

1、RykenSlimeCustomizer拥有与SlimeCustomizer相同的**保存物品（saveitem）**功能，所以在本wiki对**保存物品**不过多赘述

2、RykenSlimeCustomizer与SlimeCustomizer互不冲突，可同时共存

3、RykenSlimeCustomizer在SlimeCustomizer之后加载，所以你可以在RykenSlimeCustomizer中直接引用通过SlimeCustomizer自定义的粘液ID

## 感谢

Wiki贡献：

![Wiki贡献](https://contrib.rocks/image?repo=SlimefunReloadingProject/RykenSlimeCustomizer-Wiki)

以上人员按Wiki贡献大小排序排列

* 插件编写：[lijinhong11](https://github.com/lijinhong11)
* Wiki搭建：[HiTech0926](https://github.com/HiTech0926)
* 模板提供：[hth0987654](https://github.com/hth0987654)
