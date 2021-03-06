# mix-blend-mode: multiply


> 注: mix 有混合的意思;  blend 也有混合的意思. <br/>
> multiply 是乘，乘法的意思, 也有正片叠底的意思(将底色与前台色相乘),


One of my favorite interview questions is "how do you stay current on emerging front-end techniques and APIs?"  I always get the standard "blogs" and "RSS" answers but rarely do I ever hear "from gurus on Twitter."  I find that strange because I learn loads from Twitter, especially when it comes to CSS, because a tiny snippet can do something really neat.

我经常问的一个面试题是: “在前端领域,你如何与新技术和API保持同步更新?“  我听到的大多都是标准答案: "技术博客" 以及 "RSS订阅", 而很少听到 “关注大牛的Twitter“ 这类答案, 我觉得奇怪, 因为我从Twitter上学习 *loads*, 尤其是在学习 CSS 的时候, 一两行代码就能优雅地搞定问题。


I had heard CSS mix-blend-mode was something awesome but this blew my mind:

我听说 `mix-blend-mode` 这个CSS 属性非常给力。而实际效果也很奇妙, 比想象中还要完美:


![](01_mix-blend-mode_multiply.jpg)



Essentially, using mix-blend-mode: multiply; on an image with white background would turn that white into a level of opacity as though the image were a .png with opacity.  Whoa!  I created a demo here:

本质上, 在图片上使用 `mix-blend-mode: multiply;` 样式, 会把所有白色的部分转换成半透明的 png。

原文的演示: [https://davidwalsh.name/demo/mix-blend-mode.php](https://davidwalsh.name/demo/mix-blend-mode.php)

可编辑的在线代码演示: [http://codepen.io/wesbos/pen/QNONJa](http://codepen.io/wesbos/pen/QNONJa)




What an awesome bit of CSS!  Thanks to Wes Bos for the heads up on this nifty CSS feature!

这 CSS 简直不要太完美! 感谢 Wes Bos, 我才知道有这个漂亮的CSS特性! 大神的推特地址为: [https://twitter.com/wesbos](https://twitter.com/wesbos)



翻译人员: [铁锚 http://blog.csdn.net/renfufei](http://blog.csdn.net/renfufei)


翻译时间: 2016年5月2日

原文时间: 2016年4月13日

原文链接:  [https://davidwalsh.name/mix-blend-mode](https://davidwalsh.name/mix-blend-mode)



