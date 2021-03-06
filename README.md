# <a id="quick-start">快速入门</a>

## 关于版本控制

> 版本控制是一种记录一个或若干文件内容变化，以便将来查阅特 定版本修订情况的系统。 

> 采用版本控制系统 (VCS) 是个明智的选择。 有了它你就可以将某个文件回溯到之前的状态， 甚至将整个项目都回退到过去某个时间点的状态，你可以比较文件的变化细节，查出最后是谁修改了哪个地方， 从而找出导致怪异问题出现的原因，又是谁在何时报告了某个功能缺陷等等。 使用版本控制系统通常还意味 着，就算你乱来一气把整个项目中的文件改的改删的删，你也照样可以轻松恢复到原先的样子。 但额外增加的 工作量却微乎其微。

## Git 简介

### 历史

自 2002 年开始，林纳斯·托瓦兹决定使用 BitKeeper 作为 Linux 内核主要的版本控制系统用以维护代码。因为BitKeeper 为专有软件，这个决定在社群中长期遭受质疑。在 Linux 社群中，特别是理查德·斯托曼与自由软件基金会的成员，主张应该使用开放源代码的软件来作为 Linux 核心的版本控制系统。林纳斯·托瓦兹曾考虑过采用现成软件作为版本控制系统（例如 Monotone ），但这些软件都存在一些问题，特别是性能不佳。现成的方案，如 CVS 的架构，受到林纳斯·托瓦兹的批评。

2005 年，安德鲁·垂鸠写了一个简单程序，可以连接 BitKeeper 的存储库，BitKeeper著作权拥有者拉里·麦沃伊认为安德鲁·垂鸠对 BitKeeper 内部使用的协议进行逆向工程，决定收回无偿使用 BitKeeper 的许可。Linux 内核开发团队与BitMover公司进行磋商，但无法解决他们之间的歧见。林纳斯·托瓦兹决定自行开发版本控制系统替代 BitKeeper，以十天的时间，编写出第一个 Git 版本。

### 主要功能

Git 是用于 Linux 内核开发的版本控制工具。与 CVS 、Subversion 一类的集中式版本控制工具不同，它采用了分布式版本库的作法，不需要服务器端软件，就可以运作版本控制，使得源代码的发布和交流极其方便。git的速度很快，这对于诸如Linux 内核这样的大项目来说自然很重要。Git 最为出色的是它的合并追踪（merge tracing）能力。

实际上内核开发团队决定开始开发和使用git来作为内核开发的版本控制系统的时候，世界上开源社群的反对声音不少，最大的理由是 Git 太艰涩难懂，从git的内部工作机制来说，的确是这样。但是随着开发的深入，Git的正常使用都由一些友善的命令来执行，使 Git 变得非常好用。现在，越来越多的著名项目采用 Git 来管理项目开发，例如：wine、U-boot 等[19]。

作为开源自由原教旨主义项目，Git 没有对版本库的浏览和修改做任何的权限限制，通过其他工具也可以达到有限的权限控制，比如：gitosis、CodeBeamer MR。原本 Git 的使用范围只适用于 Linux/Unix 平台，但在 Windows 平台下的使用也日渐成熟，这主要归功于 Cygwin、msysgit 环境，以及 TortoiseGit 这样易用的GUI工具。Git 的源代码中也已经加入了对 Cygwin 与 MinGW 编译环境的支持且逐渐完善，为 Windows 用户带来福音。

-- 来源地址：[维基百科](https://zh.wikipedia.org/wiki/Git)
