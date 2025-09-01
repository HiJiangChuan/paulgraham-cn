
# 快照：1998年6月的Viaweb

2012年1月

1998年6月雅虎宣布收购Viaweb前几小时，我截取了[Viaweb网站的完整快照](http://ycombinator.com/viaweb)。当时就觉得这些资料终有一日会变得耐人寻味。

首先引人注目的是网页尺寸之小。1998年的显示器普遍袖珍得多。如果记忆无误，我们的首页恰好适配当时主流浏览器的窗口尺寸。

那时的浏览器（IE6还要等三年才问世）字体选择有限且不支持抗锯齿。要想呈现精美排版，必须将文字内容转为图片显示。

细心的读者会发现Viaweb与[Y Combinator](http://ycombinator.com)的标识存在某种相似性。创办YC时我们故意设计了这个内部玩笑。令人惊讶的是，虽然红色圆形是最基础的图形元素，Viaweb创立时却鲜有公司采用它作为logo——后来我才明白[其中缘由](https://hijiangchuan.com/paulgraham/EXTRA030-Mitsubishi-Zero)。

浏览[公司页面](http://www.ycombinator.com/viaweb/com.html)时，你会注意到名为John McArtyem的神秘人物。罗伯特·莫里斯（即Rtm）因[蠕虫病毒事件](http://en.wikipedia.org/wiki/Morris_worm)对公众曝光极度抗拒，拒绝在网站署真名。最终我们达成妥协：可以使用他的履历但隐去姓名。如今他在这方面已经[放松](http://ycombinator.com/people.html)许多。

特雷弗毕业时间与收购完成几乎同步，四天内他完成了从身无分文的研究生到百万富翁博士的蜕变。我公关生涯的巅峰之作是这篇[庆贺他毕业的新闻稿](http://ycombinator.com/viaweb/trevor.html)，配图是我在会议间隙为他绘制的肖像。

（特雷弗还以[Trevino Bagwell](http://ycombinator.com/viaweb/tlbwebdesign.html)的化名出现在商户可雇佣的网页设计师名录中。我们安插这个"托儿"是为防范竞争对手骚扰设计师名单。本以为他设计的logo能劝退真实客户，结果事与愿违。）

90年代获取用户必须依靠报刊杂志曝光，远不如现今的线上获客渠道丰富。为此我们每月支付[公关公司](https://hijiangchuan.com/paulgraham/045-The-Submarine)1.6万美元争取媒体露出。幸运的是记者们[很买账](http://ycombinator.com/viaweb/presquot.html)。

在关于[搜索引擎流量获取建议](http://ycombinator.com/viaweb/se.html)的页面中（当时"SEO"这个术语尚未诞生），我们列出7个重要引擎：雅虎、AltaVista、Excite、WebCrawler、InfoSeek、Lycos和HotBot。发现漏了谁吗？谷歌在那年9月才注册成立。

我们通过[Cybercash](http://en.wikipedia.org/wiki/CyberCash,_Inc.)公司支持在线交易——若缺少此功能会在产品评测中失分。但由于Cybercash体验糟糕且多数店铺订单稀少，我们反而专门设立页面[劝说商户采用电话订单处理模式](http://www.ycombinator.com/viaweb/cybercash.html)。

整个网站采用漏斗式结构，最终将用户导向[试用入口](http://ycombinator.com/viaweb/tesdriv.html)。当时在线试用软件尚属创新。我们在动态URL中加入cgi-bin路径以迷惑竞争对手。

部分[知名用户](http://ycombinator.com/viaweb/us.html)中，Frederick's of Hollywood带来的流量自然最高。大商户统一收取300美元/月费用，因此高流量用户令人担忧。有次计算Frederick's消耗的带宽成本，恰好也是300美元/月。

1998年6月，我们托管的所有店铺合计产生超1000万次月浏览量，在当时堪称天量带宽消耗。办公室接入两条T1线路（合计3Mb/s）。那个没有AWS的年代，考虑到服务器频繁故障，连主机托管都显得冒险。于是服务器直接放在办公室——准确说是特雷弗的办公室。作为独享办公空间的代价，他需要与6台轰鸣的塔式服务器共处。这些发热怪兽让他的办公室得名"热水浴缸"，日常靠叠放的窗式空调维持温度。

我们使用名为[RTML](http://ycombinator.com/viaweb/rtml.html)的模板语言描述页面，名义上是某个缩写，实则致敬Rtm。RTML本质是添加了宏和库的Common Lisp语言，通过结构化编辑器伪装成特定语法。

持续发布的模式使我们没有真正版本号。但当时行业媒体需要版本概念，我们便自行编造。需要制造话题时，就发布[整数版本号](http://www.ycombinator.com/viaweb/rel4.html)。顺带一提，"4.0版本"图标由我们自研的按钮生成器制作。整个Viaweb网站都用自家软件搭建——尽管并非网店——只为真实体验用户感受。

1997年底我们发布了通用购物搜索引擎[Shopfind](http://ycombinator.com/viaweb/shoprel.html)。其可编程爬虫能抓取绝大多数线上商店的商品数据，在当时相当先进。

- 英文版：http://paulgraham.com/vw.html
- 中文版：https://hijiangchuan.com/140-Snapshot-Viaweb-June-1998



更新记录：
- 2025-05-20 [HiJiangChuan](https://hijiangchuan.com) 初稿翻译，术语待验证；
