---
layout: post
title: "Hello Github"
description: ""
category: 
tags: [github, jekyll]
---
{% include JB/setup %}

一直没什么兴趣弄什么blog，总觉得麻烦。知道[github](https://github.com/)的page能用来做主页之后，就顺手做来玩玩。实在蛋疼时也好有个事做。

既然做了，就顺便分享下，希望会对别人有帮助，自己也好填上第一篇文章，当然我就大致说一下，详细的步骤自己google一把吧，网上已经太多了。

###准备工作
要用github来做主页，首先当然要有个github帐户，然后会用git，只要有了这两个就可以开始了。

###开始动手
第一步，自然是在github创建一个名为USERNAME.github.com的项目。USERNAME就是你的github帐户名，然后就可以通过http://USERNAME.github.com来访问了。如果只想放几个静态页面，那只要把准备好的静态页面放上去，事情就完了，下面的都不用看了。

###关于Jekyll和Jekyll Bootstrap
如果不满足放几张静态页面，github也可以满足的。github使用[Jekyll](http://jekyllrb.com/)作为后台，接下来做个Jekyll的项目就好了，具体步骤自己动手吧。

当然大部分人只是想搭个blog什么的，也不想自己太累，那么就要向大家介绍[Jekyll Bootstrap](https://github.com/plusjade/jekyll-bootstrap)了，一个简单的框架，提供了一些页面主题和api，包括留言评论和流量分析模块都已经有了。有了它，懒人只要直接folk它来当自己的主页项目，往里面填文章，主页也就搭完啦。

如果还不满足，自己动手改改就行了，虽然Jekyll Bootstrap不能和Django、Rails比，但做个blog还是够用的。至于能做多好，就看自己js和css的功底，还有个人审美。

###域名绑定
最后，如果不是一毛不拔的话，可以弄个自己的域名绑定到这里，github也是支持的。具体步骤可以看[这里](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)。
