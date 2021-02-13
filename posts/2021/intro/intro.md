# Nullkooland: The Intro

## 引子

小时候玩侠盗猎车手的时候，每次启动游戏就会播放所谓的“开场动画”，即 "Intro"。我很喜欢它们，乃至于舍不得跳过。随着好听的主题曲响起，游戏内容的简要走马观花地呈现，让人慢慢地进入一种期待而舒适的状态，准备好进入接下来的游戏时间。那么我也给自己的小网站写一个小小的 "Intro" 来帮我自己与浏览者进入状态吧！

资料，《侠盗猎车手：圣安地列斯》的 Intro ：
[!SA, yyds](https://www.youtube.com/watch?v=TTB6eEHCAko)

## 为啥想要？
想要一个自己能够控制的平台，悄悄地呈现自己的想法，或理性的或疯狂的或严肃的或欢脱的。人都会有展示欲，想要把自己的想法通过各种方式记录下来，或者传递给别人（这个“别人”的概念也包括了未来的自己）。可能只是觉得脑子里每天出现的想法就像放在易失性存储介质里的数据，要么总是被新的数据覆盖，要么随着时间慢慢模糊，嘈杂，最终就丢失了。需要一种持久化的方法把他们捕捉下来，放进稳定的容器中保存。也说不定这些记下来的东西能像坛子里的泡菜一样，随着时间的推移，再开封时会有新的味道。当然，这个味道只有做“泡菜”的我才能知道。

好友们都有自己的输出，我很羡慕他们，羡慕他们能静下心来写一点，画一点，说一点东西，把自己投入到什么里面，留下一些思绪的痕迹。我曾经也有这样的产出热情，不过最近找不到了。希望在有了自己的小天地之后能够找回那种感觉，至少得对得起自己搭建它所付出的精力。

## 名字何来？
$$
Nullkooland = Nullko + (o)oland
$$

*Nullko* 是我 fursona 之一的名字，而 *ooland* 来自于 *cloud-cuckoo-land*，意思是 "a realm of fantasy or of whimsical or foolish behavior"， 大概翻译成“理想国”或者“奇妙世界”~~“灯儿晃天地”~~。

想到这个名字的起因是偶然发现好友的某平台 ID 叫做 *Puckooland*，觉得十分有趣（至少从发音上）。与友对此进行愉快交流后便念念不忘：“既然 Puck 有自己的 ooland，那我为什么不能有呢！” 于是便依葫芦画瓢凑出了这个名字。

没错，这里就是努克的奇妙世界。但是说不定哪天会钻进来一只老虎。

## 撒子技术？
基于 [Blazor WebAssembly](http://blazor.net) 技术，差不多就是浏览器加载了基于 `WASM` 的 `.NET` 运行时然后在上面跑的客户端应用。博客都是用 `Markdown` 写的，在网页应用运行时直接加载 `*.md` 文件并通过 [Markdig](https://github.com/xoofx/markdig) 解析并动态渲染成各种组件。代码高亮着色使用了 [Prism](https://prismjs.com)，数学公式渲染使用了 [KaTeX](https://katex.org)。

目前使用了 [GitHub Actions](https://github.com/actions) 自动部署成静态页面并 host 在 [GitHub Pages](https://pages.github.com) 上。

### 为什么不选择已有的社交媒体平台呢？
1. 不能支持 `Markdown`，$\LaTeX\ \text{Math}$ 等功能，过于无能。
2. 我不能完全控制，深度自定义与内容备份无解，还需要担心 censorship，说不定哪天就没了！
3. 过多的社交属性与无用的功能只会降低信噪比，我的网站里只能有我需要的东西（推荐算法，广告之类的更是给👴爪巴！）。

### 为什么不选择现成的个人博客网页框架呢？
1. 我没学过前端，也不想去撸 `JavaScript`，而 `Blazor` 能够让我用熟悉的 `C#` 来撸网页。最多就需要学学基本的 `HTML` 语法（感觉写起来跟以前写过的标签式界面描述语言 `XAML` 其实也差不多），整个开发流程就像用了 `MVVM` 架构的 `WPF` 一样，甚至数据绑定一类的写起来还更舒服了，毕竟还是自己熟悉的东西用着顺手。
2. 不需要把文章都编译成一大堆 `html` 和 `js` 文件，部署的 repo 更清爽（~~心理作用~~
3. 搞工科的，多折腾折腾也不坏！体验一步一步把自己的小玩意儿搭起来的快感，就像我本科的时候有现成买得到的开发板不用偏要自己画一个 STM32F407 的最小系统 PCB 一样？虽然效果比不上成熟的框架炫酷，甚至有很多的排版或者移动端适配问题，但是以后可以慢慢改进嘛。
4. 借此机会可以学学 `Blazor`，说不定以后的项目需要网页或者跨平台 UI 的时候可以用得上呢？

## 写什么呢？
目前分成三类，因为文章类型的枚举只写了三种！

### 技术向 (Technical)
- 学习与工作中遇到的专业知识性话题，学习记录，踩的坑等。
- 使用严肃的语言，有可能会尝试用英文写以节省切换输入法的时间
- 欢迎通过 GitHub issues 勘误 ~~（如果有人看的话）~~

### 个人向 (Personal)
- 记录个人生活的见闻与情趣。
- 差不多就是给我自己以后看的。
- 会用中文写，放两句洋屁也不是不可。
- 希望各大浏览器早点支持 `AVIF` 格式，因为我想放好多图！

### 胡言乱语 (Ramblings)
- 不知道是啥，就是放在这里好玩或者测试网站功能用的。
- ~~无 可 奉 告~~

## 那就开始吧！
**Let's get started!** [!moonbear](images/moonbear.jpg "inline")