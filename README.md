# 深入剖析各种 CSS 布局技术

文章地址：[layout.imweb,io](http://layout.imweb.io/)

## 概述

本系列文章主要深入剖析了 CSS 的布局技术，非常适合想提高 CSS 布局方面的同学。建议新手等有了基础再来，因为里面有些晦涩的概念需要多琢磨理解，这很容易让新手晕乎，尤其是前面有关概念的几篇。

从概念的理解到实战的运用，从经典的 float、position 到现代的 flexbox、grids，从纯技术描述到个人的经验总结，点点滴滴融入的都是心血，希望可以为你解惑一二。也希望在你马不停蹄追赶 JS 的时候，还记得有 CSS。

## 问题场景

很多时候你觉得你的代码是对的，但是在页面中呈现出来的样子却背叛了自己。于是只好借助调试工具屁颠屁颠的调成“对”的模样，如以下场景：

- 为什么我的 `margin-top` 值不管用了？
- 奇怪了，为什么 `z-index` 的值明明比较高，但是被覆盖了？
- 神奇了，原来 `margin` 左右为 `auto` 居然可以实现居中！
- 不是说 `flex: 1` 就能等分吗，为什么我的不可以呢？
- 我去，这多出来的间隙是怎么来的？
- `fixed` 怎么不管用了？
- ...

这所有问题及更多的困惑，你都可以在该系列文章中得到解答。

## 缘由

2017 年年初，领导拉了我们几个人，说想搞门前端课程，于是我们兴致冲冲的挽起袖子就干起来了。最初估计大干4个月，这不我们有个同事把相亲介绍对象的事都推迟了，就说先一门心思搞课程，等结束了再介绍。但是谁也没料到这一封闭就是10个月。对，我没有写错，是10个月。终究历经10月打磨，成就了一门前端课程：[前端工程师 NEXT 学位](https://ke.qq.com/next/index.html)。

而本系列文章的雏形其实就是来源于该课程的第三章的布局部分，在刚过去的国庆期间，我把所有的材料再仔细整理成文再赋予一层华丽表皮，于是就有了本系列文章。

这可能是我最近几年写得最辛苦的系列文章了，也许以后都不会写了，时间总是不等人，如行文有误，还请见谅或反馈！

PS：如果说本系列文章是理论的总结，那么我的 [sheral](https://github.com/imweb/sheral) UI 库就是实践方面的总结了，如不嫌弃，敬请笑纳。



