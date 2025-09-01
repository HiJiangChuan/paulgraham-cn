



# Lisp的根源

2001年5月

（我写这篇文章是为了帮助自己准确理解McCarthy的发现。你不需要了解这些就能用Lisp编程，但它应该对任何想要理解Lisp本质的人都有帮助 — 无论是从它的起源还是语义核心的角度。Lisp具有这样的核心是它的显著特征之一，也是为什么与其他语言不同，Lisp有方言的原因。）

1960年，[John McCarthy](http://www-formal.stanford.edu/jmc/index.html)发表了一篇非凡的论文，他在编程领域做了类似欧几里得在几何学领域做的事情。他展示了如何用几个简单的运算符和函数表示法构建整个编程语言。他将这种语言命名为Lisp，意为"列表处理"，因为他的关键思想之一是使用一个称为列表的简单数据结构来同时表示代码和数据。

理解McCarthy的发现很有价值，不仅因为它是计算机历史上的一个里程碑，而且因为它展示了编程在我们这个时代的发展趋势。在我看来，到目前为止，编程领域有两个真正清晰、一致的模型：C模型和Lisp模型。这两个模型似乎是高地，中间是沼泽般的低地。随着计算机变得更强大，新开发的语言一直在[稳步地](https://hijiangchuan.com/paulgraham/012-What-Made-Lisp-Different)向Lisp模型靠拢。过去20年新编程语言的流行配方是采用C的计算模型，并逐步添加来自Lisp模型的部分，如运行时类型和垃圾回收。

在这篇文章中，我将尝试用最简单的术语解释McCarthy的发现。重点不仅仅是学习40年前某人发现的一个有趣的理论结果，而是要展示语言的发展方向。Lisp的独特之处 — 事实上，Lisp的定义性特征 — 是它可以用自身来编写。为了理解McCarthy这句话的含义，我们将重走他的脚步，把他的数学符号翻译成可运行的Common Lisp代码。

英文版：https://paulgraham.com/rootsoflisp.html
中文版：https://hijiangchuan.com/010-The-Roots-of-Lisp


更新记录：
- 2025-03-16 [HiJiangChuan](https://hijiangchuan.com) 初稿翻译，术语待验证；
