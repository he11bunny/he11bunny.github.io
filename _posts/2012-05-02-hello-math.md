---
layout: post
description: ""
category: math 
tags: [math,mathjax]
---
{% include JB/setup %}

网页上公式一直是我觉得蛋疼的地方，图片貌似一直是唯一的方法。

以前读书时我在蛋疼时就会想，当初干嘛就没有个标准呢，html不是xml嘛，各种文档不也是xml嘛。有个标准，至少有个盼头啊。结果后来知道是有个标准的，而且人家W3C定这个标准的时候我还没上过网呢，1999年MathML的第一版就定下来了，现在都已经第三版了。想想html5到现在都还是草案，看来W3C的人还是蛮热爱数学的。

但是为什么大家看不到呢，可能这不是广大群众的需求吧，好吧，是一定。其他的原因，大致就是理想和现实的差距，让ie们一直没理这个标准，当然ie也不爱理另一个标准╭∩╮-.-╭∩╮。当然面包会有的，特别是在如今RIA的时代，在浏览器里都可以玩小鸟了，MathML真心小意思了。扯了这么多，其实就是想试试这个MathJax。关于MathJax我就不介绍了，想用的自己去官网看文档吧。

下面我就露两手，给大家看看效果。如果发现下面什么都没有，直接关了吧，不好意思浪费你宝贵的酱油时间了。

####e：
$$ e=\lim\limits_{x\to\infty}(1+\frac{1}{x})^x $$

####简单公式：
$$ math=math\cup freedom $$

####复杂一点的公式：
$$ f(x)=\sum_{n=0}^\infty a^n\cos(b^n\pi x) $$

####再复杂一点点的公式：
$$ \iint_{D}(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y})d\sigma=\oint_{L}Pdx+Pdy $$

####好复杂的公式：
$$ \frac{a_0^2}{2} + \sum_{n=1}^\infty(a_n^2+b_n^2)\leqslant\frac{1}{\pi}\int_{-\pi}^\pi f^2(x)dx $$

####一大坨：
$$ \left\[ \begin{array}{c} X(0) \\\\ X(1) \\\\ X(2) \\\\ \vdots \\\\ X(N-1) \end{array} \right\] = \left\[\begin{array}{ccccc} \omega_N^{0\cdot 0}&\omega_N^{0\cdot 1}&\omega_N^{0\cdot 2}&\dots&\omega_N^{0\cdot (N-1)}\\\\ \omega_N^{1\cdot 0}&\omega_N^{1\cdot 1}&\omega_N^{1\cdot 2}&\dots&\omega_N^{1\cdot (N-1)}\\\\ \omega_N^{2\cdot 0}&\omega_N^{2\cdot 1}&\omega_N^{2\cdot 2}&\dots&\omega_N^{2\cdot (N-1)}\\\\ \vdots&\vdots&\vdots&\ddots&\vdots\\\\ \omega_N^{(N-1)\cdot 0}&\omega_N^{(N-1)\cdot 1}&\omega_N^{(N-1)\cdot 2}&\dots&\omega_N^{(N-1)\cdot (N-1)} \end{array}\right\] \cdot \left\[ \begin{array}{c} x(0) \\\\ x(1) \\\\ x(2) \\\\ \vdots \\\\ x(N-1) \end{array} \right\] \\\\
其中 \omega_N=e^{\frac{-2\pi i}{N}} $$

####很漂亮的图：
$$ f_c(z) = z^2+c, c \in\mathbb{c} $$

####还是很漂亮的图：
$$ (x^2 + \frac{9}{4}y^2 + z^2 - 1)^3 - x^2z^3 - \frac{9}{80}y^2z^3 = 0,\\\\ -3\leqslant x,y,z \leqslant 3 $$

没了……

