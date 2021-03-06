---
title: 开发更新#1
date: 2018-02-16
short_description: MDL平台在这段时间里一直在持续积极发展的状态，现已是时间可以于社区分享一些更新要文。
image: images/80/2018-02-16-development-update-1.jpg
next_article: /zh/2018-02-16-development-update-1
prev_article: /zh/2018-01-31-pre-ito-hard-cap
lan: zh
categories: ["Development"]
---



亲爱的在区块链伙伴们和MDL的支持者们：

MDL平台在这段时间里一直在持续积极发展的状态，现已是时间可以于社区分享一些更新要文。

我们的MDL里目前有大约六个开发中的项目。他们中的一些项目从第一天开始便是开源代码（钱包、teller、这个区块链、博客、网页），而其他一些正在进行内部开发和内部测试中（平台后端、Android客户端，等等）。

我很高兴地宣布，我们的开发团队已发展到了六人。伴随着我们团队如此之快的发展，现在我们更重要的是把我们手头上的优先事项和重点任务，分配给最合适的、合格的人。

说到重点，我们的ITO已经接近了，这就是为什么我们的大部分精力都花在建立钱包，testnet和MDL的区块链（明显的模型/奖章/M.D.L.）代币，修复了teller的所有功能，同步和固定了节点和准备了热钱包解决方案。

在今天的更新中，我将关注开源项目。

MDL testnet 节点 -> mainnet 节点，钱包

https://github.com/MDLlife/MDL

MDL是基于天空币的代码。这就是为什么我们花时间在内部进行测试的原因。我们还没有看到任何致命的问题，但仍有一些小的（微不足道的）bug正在修复中。核心功能已经是可行的，同时天空币团队一直努力在提高自己的平台，现在已经有1000多个Git提交的主要空分。我们正在同步，并将它们合并到我们的代码中。

由于在代码库中的一些变化，我们有大部分仍然需要手动操作，以便不打破我们的工作代码。从产生在2018-01-25 03:51的创世记区块以来，MDL代币已分发到100个地址（10000000 MDL/地址）和24个人了，这些代币已经被锁定了1年，还有另外20个地址已经被锁定了2年，按照我们的路线图/开发计划。其余的代币也已经都安全离线存储了。

我们已经从第一组10000000 MDL中分离了100 MDL进行内部测试。我们将继续进行测试，直到ITO的开始。这意味着，除非在这不太可能发生任何严重的漏洞情况下发生bug，这将成为mainnet blockchain，这是有趣的开端！

代币的当前最小分度为0.001 MDL MDL，一旦MDL允许更多的用户加入平台，将有可能把一个代币的最小分度调整为0.000001 MDL（6位小数），但我们决定在6位小数之后不再多加小数点，因为那已经是不必要的了。基于天空币的加密货币拥有最多6位小数点，这令更多的人不容易出错。但目前我们不希望网络上泛滥微交易。代币小时数和他们应有的行为也正在进行中，我们将在不久的将来提供这部分的更新。

ITO 工具，teller

https://github.com/MDLlife/teller

MDL艺人社正在完成法律方面的问题，这将决定我们如何执行KYC。在ITO期间为我们的teller列出MDL白名单地址，最可能是我们要走的路。这就是为什么我们一直在修理teller。MDL提款计划支持以下转换：

BTC -> MDL
ETH -> MDL
SKY -> MDL
WAVES -> MDL
当然，我们早期的投资者将能够通过teller交换他们的基于Waves的MDL.life（预售MDL）代币

MDL Explorer

https://github.com/MDLlife/explorer

MDL Explorer将通过运行MDL节点局部先，然后再运行资源管理器。目前于天空的浏览器没有太大的差异，如果你运行它，你甚至会在许多地方看到Skycoin。这是我们不久之后将要改变的事情之一。【提高Explorer赏金和将其品牌更名为MDL？】此外，我们将建立一个服务器来全球化运行MDL Explorer。但是别忘了，每一个MDL钱包的最后一个标签就是自己的Explorer噢。

我们的设计师团队和我们的概念团队正在完成MDL新品牌的手册/样貌的过程中。这就是为什么上述产品的设计并不是我们的首要任务。一旦新的设计，标志和企业的颜色得到确认，我们将更新和改进设计。

因为所有的项目都是开源的，感兴趣的开发者将有机会克隆和编译代码本身，请遵循GitHub指令。

为所有流行的系统安装的钱包版本（MAC /Win/ Linux）在不久后便将可以提供给我们的社区成员。事实上，那些喜欢Go语言的人已经可以用gox编译它了 ;)

地址：MDLzVebXKCqbtGJMnEoGdFkewvUN5KMryrRTc https://github.com/MDLlife/MDL/pull/1

我们正在考虑增加三个字节（确切地说，“MDL”）在每一个MDL令牌地址前，让它更清晰可辨，消除不小心把MDL代币发送到天空币或者太阳币等等地址的可能性。这还没有最终决定我们成本和风险的估计，但代码已经写好了。详情请见上方的第一个pull request。

我会尽快在下次开发更新中尽可能详细地介绍我们的内部项目。
现在我的手和脑袋必须从英语切换回golang，因此我们的支持者，艺术家，预约者和所有区块链人员将更快获得更多精彩的东西。

此致敬礼, MDL.life's CTO, RT, Gladenbach

