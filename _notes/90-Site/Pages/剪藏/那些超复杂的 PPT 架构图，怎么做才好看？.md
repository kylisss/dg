---
url: https://mp.weixin.qq.com/s/L8V64HTXmHWUXekopxWv4w
title: 自动导入标注到 Obsidian（不使用同步助手方案）
date: 2023-01-31
tag: 
- PPT设计
summary: 
---

> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码，原文地址 [mp.weixin.qq.com](https://mp.weixin.qq.com/s/L8V64HTXmHWUXekopxWv4w)

废话不多说，直接看几张反面案例：

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbMIrVicUyaLyGkogS0OqvS5XbmeFxkKKYkR9ful6LtnzPAIH2miafmuOw/640?wx_fmt=png)

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbOa6z58pvjcp8IcjlMueYe5k7a5wiajuV90ebbp0lft51vd0NhCaDLZw/640?wx_fmt=png)  

信我，像这种又丑又复杂的架构图，其实你只要理解以下两个设计思路，就能让它们有很大改观：  

*   缕清层级关系；  
    
*   递减式地使用颜色；
    

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbaDCsphpxPTTscKsQWnXgawDmzkjOVxRVhVw2GXYiaNRmPaw655dZITA/640?wx_fmt=png)

我直接改一下前面的案例给大伙儿看看![](https://mmbiz.qpic.cn/mmbiz_png/b96CibCt70iaajvl7fD4ZCicMcjhXMp1v6UibM134tIsO1j5yqHyNhh9arj090oAL7zGhRJRq6cFqFOlDZMleLl4pw/640?wx_fmt=png)，你们就明白我在扯啥了。

**▎****案例修改实操**  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbMIrVicUyaLyGkogS0OqvS5XbmeFxkKKYkR9ful6LtnzPAIH2miafmuOw/640?wx_fmt=png)  

当图表中的模块数量比较多的时候，你要做的第一件事，就是缕清模块之间的**信息等级关系**。

比如在这个模块中，信息的等级关系就非常明显：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbOM4fZfkSib0Ct3s1t0187ehJEqWYMuCvg4JLlctAIJ5hk5DxypYibxYA/640?wx_fmt=png)

缕清了等级关系，然后呢？  

然后你就需要为它们使用显眼程度不同的设计样式，最简单的方法就是——**递减式地为它们使用颜色**。  

比如，一级标题用最显眼的彩色形状来承载，二级标题用彩色文字，三级标题用白色形状来承载：

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbfHdaR3flK9px9tqwq1jpY9nyPtCLRgxoxm1JbzNtZOic31SqPbPT2yQ/640?wx_fmt=png)

你瞧，现在信息的结构是不是很分明？而且配色也轻盈了不少。

另外在上图中有一个**细节**——我为用来装载信息的模块使用了最不显眼的渐变白色。  

很多小伙伴在做这种架构图时，都会下意识地认为模块也需要填充颜色，这正是导致你的架构图显得很臃肿的原因。  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbibuicnL1nNmnQEc8Yvhj5ianUyHf1l0LRFtlVMJlAqBx9IMIzw9e7Rh7g/640?wx_fmt=png)

当你能理解 “**根据信息等级，递减式地用色**” 这句话时，你就能做出下面这种信息等级清晰、配色轻盈的架构图了：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbnlqjXpIEDWPZrrWSA2bHu1FGppPQnPwBX41shLrRcX8c89nrnQ8eNQ/640?wx_fmt=png)

为了帮大伙儿加深印象，我们再用一模一样的设计步骤来修改一下这个案例![](https://mmbiz.qpic.cn/mmbiz_png/b96CibCt70iaajvl7fD4ZCicMcjhXMp1v6UibM134tIsO1j5yqHyNhh9arj090oAL7zGhRJRq6cFqFOlDZMleLl4pw/640?wx_fmt=png)，不过这次我们尝试换成**深色背景**：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbsSmMvnbcZsbNtULgLFjrwiaWpFZofEfaIoDAibk1W4NGZJpCkJQhLqdA/640?wx_fmt=png)  

先缕一下模块中的信息等级关系：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbrctABzPEZF89frhmn658omaPx3iaYKFMZwhr4lSx2pLOXTvjmTHuS1Q/640?wx_fmt=png)

接着，继续根据等级关系，为它们使用 “显眼程度递减” 的配色：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbgTKhUgZVibMdmGSklx2kThOaxT2zT8fe5H4WAjNvRCQahtw6e7iaTolA/640?wx_fmt=png)

最后，把这个配色套路应用到所有模块中，搞定![](https://mmbiz.qpic.cn/mmbiz_png/b96CibCt70iaajvl7fD4ZCicMcjhXMp1v6UibM134tIsO1j5yqHyNhh9arj090oAL7zGhRJRq6cFqFOlDZMleLl4pw/640?wx_fmt=png)：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbwur7IhOF7Ml7CHd1vSFH52eZgLzicNvrcIGxZ4w0gzl4MAn898TyMnA/640?wx_fmt=png)

你瞧，只要思路对了，各种不同配色的架构图我们都能 hold 住。  

OK，如果你只是想应付一下领导，那你看到这里就可以拉到末尾去点【**赞**】，然后关掉这篇小破文了![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbB3ZYhlpekibf3WJyzibaIKuPT9Pn2oDf79usLovwboBiaLP09zEv70YBg/640?wx_fmt=png)。

要是你觉得自己还年轻，作死欲望强烈，那你可以继续往下看，我再给你介绍多一种耗发量惊人的架构图做法。  

**▎****案例延伸**

当领导说他想要一个 “立体架构图” 时，也许这是你以为他想要的效果：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbOa6z58pvjcp8IcjlMueYe5k7a5wiajuV90ebbp0lft51vd0NhCaDLZw/640?wx_fmt=png)

直到 3000 块的工资被扣了五毛二时，你才发现原来他想要的是这种![](https://mmbiz.qpic.cn/mmbiz_png/b96CibCt70iaajvl7fD4ZCicMcjhXMp1v6UibM134tIsO1j5yqHyNhh9arj090oAL7zGhRJRq6cFqFOlDZMleLl4pw/640?wx_fmt=png)：

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbzYSAOoOexqcz6Tic1qGoY00DLBxMqKXCBEx6ADlA0NN9Qat8SmJATBA/640?wx_fmt=png)  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbeA4Bib08hqOMX3BrQtprkCTHcY5Itn9UUq0aVYicyW0w2mWVmDibic1pZQ/640?wx_fmt=png)

▲2021 阿里巴巴云栖大会 PPT

骚年莫慌，今天我就教你怎么把这五毛二要回来。  

就拿前面那个肇事的案例来开刀。  

这里我们先根据信息的三层结构，插入三个普通的椭圆形，再为其设置【**渐变填充**】，有空间感的 “立体平台” 就是这么来的：  

![](https://mmbiz.qpic.cn/mmbiz_gif/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbYeYZibagOJWVjr2n3syofJLcliazpMHibbVDKRlaicB4cy0CNXLzLezl5w/640?wx_fmt=gif)  

为了让整个平台看着更丰富，我们还可以给不同圆形使用不同样式，或是换成其他素材：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbDFWG4pmSA5fHU5aIncwmV6hUIzRZNmjCELTHk9obek0I64BvUsJ0iag/640?wx_fmt=png)

接着把文字补充上去，图表雏形就出来了：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbZ3grRdN39SoibXicloFxwKQicHNxwWwsOiaOmQFticZdMdD6hqjOe17royg/640?wx_fmt=png)

最后，再插入设置了渐变色的箭头形状，营造出上升的趋势感，同时再加些装饰物进去，搞定：

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbYGsibVV5UeRJzj4dLnyxecmSNzrRfWNNCKgHriayN6kTn8TrzeB1Fwwg/640?wx_fmt=png)

好了，现在你可以拿着这页 PPT 去跟领导要回你那五毛二了，不谢。  

另外，除了圆锥式的架构图，像下面这种**立方体架构图**也是用同样的方法做出来的，只不过就是把椭圆形换成了平行四边形而已：  

![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbIgUjciafqMibq9mCMwn945yUpdBxJVublP041FxcPA2Pt1l4Z97pntWg/640?wx_fmt=png)

**▎****总结**

现在我们来总结一下以上内容：  

*   **绘制平面的架构图**：先内容的缕清层级关系，再递减式地为元素配色。  
    
*   **绘制立体的架构图**：先根据层级数量，插入对应数量的形状，再为形状设置渐变色。
    

最后哔哔多一句，立体的架构图看着是挺帅，但是适用范围其实不大，而且很费时费力。

所以，大伙儿最好把主要精力放在平面架构图的学习上，领导实在要扣那五毛二就给他吧![](https://mmbiz.qpic.cn/mmbiz_png/HvhdY1Fv6EP1OJlX1LAwkzDhExwgvPwbB3ZYhlpekibf3WJyzibaIKuPT9Pn2oDf79usLovwboBiaLP09zEv70YBg/640?wx_fmt=png)。
