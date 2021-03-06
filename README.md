# The Wheel -创意轮盘-
~~不满于管杀不管埋的拉跨微软，抄袭surface dial创意制作的~~ 

基于Qt制作的轮盘小程序，可以有效的帮助你省下对微软•画大饼•部门的赞助金，本程序专业名称为——多逻辑可视化快捷键调用程序（误


## 简述
程序的整体逻辑很简单，无非就是调用快捷键对程序进行操控。

适用场景一般为绘画……嗯，没了，毕竟我只把它用在了画画上_(:з」∠)_ 。

其他适用场景诸如影音编辑、工程绘图什么的~~那都是微软吹出来的~~，没有实际操作过，不予置评。

但理论上只要是快捷键能达成的操作，本程序都可以代为实现。

创意轮盘，本意即为『实现你的创意』。

***

程序通过『**命令**』-『**轮盘**』-『**方案**』来实现对不同适用场景下快捷方式的调用。

所有配置都可以自己自定义，最大程度满足每个人不同的使用需求。

>『**方案**』中包含若干『**轮盘**』，『**轮盘**』中对应相应『**命令**』。

<br/>

-『**方案**』对应为适用场景，用户可以针对不同的应用设定不同的『方案』。

-『**轮盘**』则为表现条件，分为“无环轮盘”、“进度环轮盘”、“自定义轮盘”三种展现形式。

-『**命令**』则是程序的核心功能，通过可视化的方式对程序快捷键进行调用。

>不过说实话，因为没有对应的API，对相应的程序进行针对性配置，“进度环轮盘”和“自定义轮盘”只是空有花架子的样子货而已，实际使用上我也只是使用了“无环轮盘”，仅音量控制因为有系统API支持，音量控制的“进度环轮盘”的表现还算能看。

![图片0](https://s3.bmp.ovh/imgs/2022/03/dfd774154a53e67b.png)

***

关于『**额外工具环**』，其实一开始只有旋转轮盘一种命令调用方式，毕竟是对surface dial的“致敬”。外加我测试时使用的是sai1，实际支持的快捷键种类很少。『**额外工具环**』是提供给群友内部测试时，群友提出来的想法——“能不能调用单一快捷键”，我才知道sai2原来支持通过快捷键调用绘制工具，有了目的地明确的使用场景，添加一个调用逻辑自然不麻烦，于是『**额外工具环**』模式新鲜出炉。

>没错，『额外工具环』拖动调用的操作逻辑也是抄的，就是电脑版sketchbook左下角那个可能大家都不常用的边角工具，要加操作逻辑时我第一时间想到的就是这玩意，虽然因为位置原因，我电磁笔都不爱往那去，导致使用次数屈指可数，但操作逻辑是真的挺有意思的，导致记忆犹新。

![图片4](https://s3.bmp.ovh/imgs/2022/03/f600518776270abe.png)

## 教程

**双击主轮盘拖动为切换工具轮盘。**

**单击主轮盘拖动为调用轮盘命令。**

**双击主轮盘中心拖动至额外工具环图标为执行拖曳命令。**

**单击主轮盘中心拖动为程序界面移动。**

[使用教程](https://github.com/kongbaiku/The-Wheel/wiki/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B)

## 下载

[GitHub下载](https://github.com/kongbaiku/The-Wheel/releases)

## 其他
图标选择页面是基于[飞扬青云](https://github.com/feiyangqingyun/QWidgetDemo)大神QWidgetDemo中的iconhelper修改而成，在此基础上添加了图标手动换色功能，感谢大神对于Qt的贡献。

程序主图标自来[icons8](https://icons8.com/)，工具图标来自[Awesome](https://fontawesome.com)。

## 演示
程序使用演示（基于sai2）

**1.旋转轮盘演示**

![演示1](https://s3.bmp.ovh/imgs/2022/03/f01361379dce5d02.gif)

**2.拖曳轮盘演示**

![演示2](https://s3.bmp.ovh/imgs/2022/03/2c323b0e1bc12ab5.gif)

**3.进度环轮盘演示**

![演示3](https://s3.bmp.ovh/imgs/2022/03/a289e72f7de5ac21.gif)

**4.自定义轮盘演示**

![演示4](https://s3.bmp.ovh/imgs/2022/03/8e46165f1aba0647.gif)
