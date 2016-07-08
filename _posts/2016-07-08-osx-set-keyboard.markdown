---
layout: post
title:  "<转>【干货】谈谈外接键盘在os x中的设置技巧（不仅仅是换苹果键）"
date:   2016-07-08 14:08:12 +0800
categories: MAC
---
>  本文由　[小鸡炖蘑菇-TuringMachine123](http://www.zealer.com/personal/116610)　发表于　[ZEALER](http://plus.zealer.com/post/8918#rd)

----

这是自己好久以前发在贴吧里的帖子，看到咱这个小组里也有用macbook外接机械键盘的，所以想到拿出来分享一下。。。

![](http://img0.zealer.com/55/59/2a/d57ec8fb42da28de62a368b3e4.jpg?imageView2/3/w/690/h/0)

Mac自带键盘有独特的f区快捷键和强大的触控板，却存在着键程短和触感反人类的劣势，因此对于需要长时间输入的mac用户来说，配一个机械键盘显得十分必要。但机械键盘大多是按晕头死排布的，虽然在mac上也能用，但会有些别扭。也有某些键盘，宣传支持mac os，结果只是送了两颗command键帽而已。所以楼主结合自己用mac和机械键盘的经验，和大家分享下mac中设置外接机械键盘的一些技巧。

楼主的主力键盘是wasd的87绿轴，OS X排列，打开背面1号开关就是mac模式，实际上这个模式也不能完全达到和自带键盘一样的效果。如果是没有特殊mac模式的机械键盘的话，情况会更复杂一些。
晒一张我的使用环境，可以看到外接键盘后，自带键盘和触摸板距离手都太远，不方便使用。所以对设置机械键盘的目的应该是尽量便捷的实现自带键盘的快捷键和触摸板的手势功能。

![](http://img0.zealer.com/a4/c5/9b/e18a9f211a5a20a774693f9a7a.jpg?imageView2/3/w/690/h/0)

### 【基础篇——苹果键的设置】

首先是苹果键，也就是command键，这颗按键在晕头死排列中并不存在。在初次连接外接键盘时，os系统会自动弹出键盘的设置。你需要按照提示在外接键盘上找到相应的按键并且按下来进行识别。如果系统没有自动弹出提示，也可以通过**“系统偏好设置”—“键盘”—“更改键盘键盘类型”**来进行识别。识别之后，系统会将键盘上的Windows键映射成苹果键，alt键映射成option键。

![](http://img0.zealer.com/9f/10/17/ba2b410339bc34ff81702bb7f4.jpg?imageView2/3/w/690/h/0)

![](http://img0.zealer.com/95/8b/ed/21259db02df18c6117c72734d1.jpg?imageView2/3/w/690/h/0)

![](http://img0.zealer.com/c6/bb/67/aa6af3dc161a089060b4b01003.jpg?imageView2/3/w/690/h/0)

这里还有一点小问题，对使用mac键盘布局的人来说，系统自动识别之后，command和option键的排布是和习惯相反的。在mac键盘中，苹果键应该在alt的位置，而option则在windows key所在的位置，这时候可以用键盘设置中的 **"修饰键…"** 进行修改。最后把alt和windows的键帽拔出来互换以防视觉上的混淆~ 完成后，可以通过command-C 和 command-V进行测试。

![](http://img0.zealer.com/42/c4/85/723d0328ed311a76e7bd20292b.jpg?imageView2/3/w/690/h/0)

### 【进阶篇——触摸板手势的代替 & f区快捷键的实现】

#### 触摸板手势的代替

mac的触摸板功能很强大，使用频率也很高，而且这些手势可以用键盘组合键代替。但组合键毕竟难记，再加上大多数机械键盘在mac上有些键用处不大（如87或104键盘多出来的f区或功能区），如果能将这些复杂的组合键转化成单键功能，可以大大提高日常使用效率。

一种简单的办法是在系统键盘设置中设置快捷键。手势的功能大多集中在Mission Control中，可以按照自己的喜好设置，建议改成F区的多余按键。

![](http://img0.zealer.com/4a/93/37/0c06ae5f6da66fdd72b8336a8b.jpg?imageView2/3/w/690/h/0)

还有一种方法可以将功能区的按键也改成快捷键，需要插件的帮助。（系统自带的键盘设置并不能识别功能区的这些键，完全为os x设计的键盘除外）具体设置我写在究级篇里了。

#### F区快捷键

对于mac键盘，默认f区的功能：

F1-F2：屏幕亮度调节；

F3：Misson Control;

F4: Launchpad;

F5-F6: 自带键盘亮度调节；

F7-F9：媒体控制；

F10-F12：音量调节；

![](http://img0.zealer.com/cd/40/09/e92669780d70fe169c5f9f8581.jpg?imageView2/3/w/690/h/0)

想要把普通键盘的f区也改成这些功能，用系统自带的设置已经做不到了,需要插件『Karabiner』的帮助，这是mac上一款可以随意更改键盘映射的软件，默认的选项已经十分丰富，并且支持脚本编写，功能很强大。

安装完成后桌面上菜单栏会有一个正方形图标，点击后选择 **"Pereference"**：

![](http://img0.zealer.com/04/a5/ab/4f62560ec32232356c2eab5d56.jpg?imageView2/3/w/690/h/0)

在 **"Change Key" **默认的选项中找到**"Change F1..F19 key & Functional Key"—"For PC keyboards"**, 然后勾选你需要的快捷键方式（可以是直接把f区映射成上述功能键，也可以通过fn   f区按键实现）

![](http://img0.zealer.com/a7/4d/50/3e4e9bb3c5f268c6208c00dbc3.jpg?imageView2/3/w/690/h/0)

### 【究级篇——脚本编写】

我们先不谈上文遗留下来的功能键代替手势问题， 先来看看有些键盘的功能区是这个样子的：

![](http://img0.zealer.com/2c/2d/b3/43ee7abec85e94d3c6cd4d1b71.jpg?imageView2/3/w/690/h/0)

这些媒体和音量控制键在mac中是不起作用的，即使karabiner也没有默认的对于这些键的改动。这时候karabiner提供了脚本编写功能，你可以自定义这些键的用处，通过编写脚本让软件识别。

<br/>
过程：在菜单栏右边找到图标，单击-> **Preferences**;

切换到 **Misc& Uninstall** 标签;

点击 **Open private.xml** 按钮，在弹出的界面打开 **private.xml**;

默认只有两个root标签，代码写在标签里就好。

<br/>
写代码就是简单的xml了

首先是对文件的描述(最后一行一定要，标签中写什么随意，描述一下脚本功能就可以)

比如：

Functions

volume&music

remap.volumeKeys

<br/>
然后就是自定义键位，大体可以分为两种：

**第一种是把指定的键定义成指定的功能**

格式是：

--KeyToConsumer--KeyCode::你要改的键,

ConsumerKeyCode::想要实现的功能

<br/>
例如: 把pageup键改成音量增加的功能：

--KeyToConsumer--KeyCode::PAGEUP, 

ConsumerKeyCode::VOLUME_UP

那么之前的替换手势的想法能不能用第一种情况实现呢，建议不要，因为手势功能不像媒体和音量控制有专门的术语（其实是我还没找到）。。。

**这种情况可以用单键代替组合键的格式来写（注意顺序）：**

--KeyToKey-- KeyCode::单键,

KeyCode::组合键中后按的键,

ModifierFlag::组合键中先按的键（例如ctrl，command之类）

<br/>
例如: 把F10改成四指右扫向右移动一个space的功能（组合键是control →）：

--KeyToKey-- KeyCode::F10,

KeyCode::CURSOR_RIGHT,

ModifierFlag::CONTROL_R

<br/>
上述代码需要按键对应的KeyCode，像F1，F2。。。或普通字母键这样简单的按键，按键本身就是它的代码，比如A键的代码就是KeyCode::A。

对于比较复杂的按键如control，option，或者是像方向键这种没有字母标注的键，『Karabiner』提供了**eventviewer**组件，Eventviewer 可以捕捉你的按键动作并给出相应的按键信息，其中就包括按键代码。

点击菜单栏上的方形图标选择 **"Launch Eventviewer"**：

![](http://img0.zealer.com/2a/ac/8e/7269bfdd59b73011eb11c4e2ed.jpg?imageView2/3/w/690/h/0)

之后会弹出这样的表格界面

![](http://img0.zealer.com/3b/5f/d6/b560c07ca5330620d16451a9ab.jpg?imageView2/3/w/690/h/0)

此时每按下一个键，表格里都会出现相应的键的信息，注意我们这里需要的KeyCode不在『**code**』栏中，而是『**misc**』栏中显示的内容。如上图显示，左ctrl的代码就是CONTROL_L。

这样编写脚本就很简单了，你的机械键盘在mac系统中也能随心所欲的使用了~
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/