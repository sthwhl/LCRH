[#]: collector: (bestony)
[#]: translator: (Mikedkmilk)
[#]: reviewer: ( )
[#]: publisher: ( )
[#]: url: ( )
[#]: subject: (Command Line Heroes: Season 3: Diving for Perl)
[#]: via: (https://www.redhat.com/en/command-line-heroes/season-3/diving-for-perl)
[#]: author: (RedHat https://www.redhat.com/en/command-line-heroes)

命令行英雄 第三季:深入聊聊Perl语言
======
**00:02** - _Saron Yitbarek_

想象一下Perl语言的创建者Larry Wall在1999年的一次会议上拿起麦克风，留着他标志性的浓密小胡子和梳理过的刘海，感觉相当好，因为他所发明的语言正在越来越受欢迎。


**00:19** - _Voice actor_

声音测试。

**00:19** - _Saron Yitbarek_

Perl语言是不是轻松地超越了COBOL、Visual Basic和Python?Larry Wall开玩笑得说,“Python仍然是一个遥远的竞争者”。Wall从dice.com的一份报告能看到这次参加集会的人数非常多，在那时来看Perl语言的未来是非常非常光明的,然而之后Perl的未来就不再如此了。dice.com在20年后的2018年夏天将Perl列为最可能灭绝的语言之一。短短20年之间发生了什么?

**00:59** - _Saron Yitbarek_

我是Saron Yitbarek，本节目是命令行英雄，一档红帽公司的原创播客。这一季是关于我们编程语言的力量和前景的。在上一集我们追踪了JavaScript在互联网上的疯狂崛起。

**01:19** - _Saron Yitbarek_

但并不是每一种语言都有一个不断成长和成功的故事。大多数语言出现并在当时非常特殊的生态系统中发挥了它们的作用，然后当我们的编程生活里需要其他类型的工具时它们就开始消退。


**01:37** - _Saron Yitbarek_

本集我们将深入介绍Perl世界。是什么导致了它早期的成功，为什么它的成功突然就被颠覆了?我们生活的环境，我们的基础设施，我们的硬件，所有的因素都会决定哪些语言会繁荣，哪些会开始萎缩。这就是Perl语言的故事里如此吸引人的地方。


**02:08** - _Saron Yitbarek_

我们知道Perl并没有统治世界，但是退回到90年代的时候Perl语言的一切都不是那么确定。Tim Berners-Lee在1991年发明了万维网，之后便迅速创造了一个全新的基于网络的发展领域。谁也说不准会是哪种编程语言在这个新领域取得成功。


**02:31** - _Michael Stevenson_

在互联网出现的时候所有人都等待着会有什么事情发生。那个时候整个世界都是令人兴奋的。


**02:39** - _Saron Yitbarek_

Michael Stevenson是阿姆斯特丹大学媒体研究的副教授。他为我们描述了早期的Web。人们见过Usenet，也见过ARPANET。他们在网上看到了美国，还有其他一些国家。但是直到网络出现互联网的全部发展潜力才真正得到体现。突然之间，你就进入了这个巨大的互联世界。这是一个出乎意料的事情。

**03:09** - _Michael Stevenson_

你一定会记得1993年，那一年正是网络开始崭露头角的时候，也是《连线》杂志开始出版的那一年。在那之前类似《Mondo 2000》这类的杂志真的让电脑看起来像神秘知识的来源，让电脑看起来很酷。

**03:32** - _Michael Stevenson_

因此从这个意义上说，网络也到达了一个相当特定的时期，那时候人们已经准备好对这样的网络技术感到兴奋。

**03:43** - _Saron Yitbarek_

故事在这个时候开始了：Larry Wall在1987年创建了Perl，4年后人们才对万维网开始兴奋起来。Larry Wall最初提供给世界的Perl就是一种通用的Unix脚本语言。这当然很有帮助，但同时Perl还有一些秘密元素，这些元素将使它成为即将到来的web开发世界的理想语言。

**04:14** - _Michael Stevenson_

令我们比较周知的是Perl是在Larry Wall参与的一个秘密国家安全局项目中发明的，基本上他所做的就是创建一个类似Usenet新闻类的破解版本，因此Perl语言从一开始只是文本操作和将数据从一个地方移动到另一个地方，这完全符合web的需求。而Perl作为一种易于使用的脚本语言，更接近于自然语言。它可以用来快速开发东西，所有这些都让Perl成为了一个完美的组合，不仅适合专业用户，也适合新加入的业余用户。

**05:09** - _Saron Yitbarek_

很偶然得是Perl在出现时就能适用于网络。Larry Wall不可能知道网络即将出现。但当它出现时事情就相互吻合了。但我认为还有一点很关键：Perl是一种自由语言。拉里·沃尔在GPL协议下发布了它，而GPL是由自由软件基金会开发的通用公共许可证。

**05:37** - _Saron Yitbarek_

Larry Wall让他的语言自由开源的决定完全符合一种新的基于web的思维方式，这种思维方式刚刚开始出现，同时Perl在其他方面也很有前瞻性。

**05:50** - _Michael Stevenson_

Perl在某种意义上是非常开放的，它总是愿意集成其他新的东西。这和Larry Wall的身份很相配。他是个很开放谦虚的人，总是仔细考虑别人的想法，并试着设身处地为别人着想。对我来说Perl作为一种语言和一个社区的特性如何在很长一段时间内真正适应这种特性是很有趣的。

**06:27** - _Saron Yitbarek_

同样Perl非常适合网络早期的狂野西部阶段，也就是黑客时代。实际上Perl的座右铭之一就是“有不止一种方法可以做到这一点”。


**06:39** - _Michael Stevenson_

在Perl的鼎盛时期和试验性的开放网络的鼎盛时期之间存在着一种近乎浪漫的联系，而在此之后网络就被几个平台所主导支配了。


**06:56** - _Saron Yitbarek_

还记得90年代是互联网历史上的一段启蒙时期，那时人们还在争先恐后地想知道还有哪些是可能的。那时对编程的需求是巨大的，每个人都需要有一个网页，这意味着一群全新的开发人员，他们都对新的做事方法持开放态度。问题变成了“好吧，我们有了一个全新的领域，但用什么语言来完成这项工作呢?”


**07:26** - _Saron Yitbarek_

Perl虽然并不是这个问题的最终答案，但对于很多人来说Perl是他们首选的语言。


**07:34** - _Michael Stevenson_

我并不是说我宁愿使用加载速度超慢的网页，也不使用谷歌搜索引擎，但当时有一些人在他们的宿舍里创建了一个类似slashdot的东西，这个东西当然很不错。我确实认为那个时代有一些特别的东西，而现在随着网络已经变得如此主流、专业化和被集中在几个大公司中，我们确实怀念那个时代。对我来说，Perl语言的出现比那个早期的任何其他故事更有代表性。


**08:15** - _Saron Yitbarek_

Michael Stevenson是阿姆斯特丹大学媒体研究的副教授。


**08:24** - _Saron Yitbarek_

之后随着90年代的到来Perl作为一种能适应早期互联网发展潜力的语言出现了，Perl是适应那个年代的语言。Larry Wall和他所创造的Perl正好了解到了网络的的本质。


**08:40** - _Mike Bursell_

在网上你可以随意搜索，也可以创建即时网页，这是互联网的美丽新世界，你可以实时地做这些事情。

**08:52** - _Saron Yitbarek_

这位是Mike Bursell，红帽公司的首席安全架构师。Mike是90年代中期发现和使用Perl的黑客之一。


**09:00** - _Mike Bursell_

对于早期的互联网来说，Perl是许多人的起点。Java语言还处于早期阶段，它在文本输入输出方面并不是很出色。如果您想进行查询和生成页面，Perl正是人们使用的工具。


**09:22** - _Mike Bursell_

Perl非常适合，因为它擅长获取文本，并使用文本做其他事情，而这正是互联网所需要的。


**09:31** - _Saron Yitbarek_

顺便需要说一下的是Larry Wall有语言学背景，这就解释了为什么Perl有强大的文本解析能力。正如Mike Bursell提到的，这是一笔巨大的红利，因为在早期网络主要是一种基于文本的媒介，因为那时候人们没有足够的带宽来处理图像。


**09:51** - _Mike Bursell_

那时候网络很容易使用，也很容易复制资料。人们在分享方面非常开放，而且很快就产生了成果，这些都是好东西。


**10:02** - _Mike Bursell_

哦，当然还有一件事，那时候你可以在网络上来收发东西。人们已经很习惯了，即使是离线测试也很容易，这些都非常有用。

**10:13** - _Saron Yitbarek_

尤其对那些在基于互联网世界中重新规划自己生活的系统管理员来说非常有用。


**10:21** - _Mike Bursell_

Perl是系统管理员的真正礼物。即使在那个年代，如果你做一些有趣的事情，你将会得到很多日志。管理这些日志，分解它们，搜索它们，并能够以不同的方式显示它们，或获取任何其他大型文本库，这基本上就是日志，甚至可以对他们进行调试。除非您要在命令行里用管道方式传输orc, sed，stuff以及ed命令，那样的话你很快就会变得非常痛苦，而Perl正好适合让你去处理这些事情。


**10:55** - _Saron Yitbarek_

到90年代后期，Perl 5已经团结起来一个强大的用户社区。像Fortran和C这样的旧语言依赖于庞大而昂贵的硬件，而Perl更有生命力，也更容易移植。在那样一个硬件成本急剧下降的世界里Perl正好得到了蓬勃发展，Perl让所有的新程序员快速而轻松地工作。这是因为拉里·沃尔牺牲了CPU和内存的需求，使Perl语法更人性。所有这些元素组合在一起使Perl成为一种很受新开发社区欢迎的语言。

**11:36** - _Mike Bursell_

在一个正在壮大的社区里，你可以去和社区的人聊聊社区里的事情，然后PerlMonks论坛出现了，那里是一个讨论的好地方，能在论坛里知道正在发生的事情。


**11:50** - _Saron Yitbarek_

这个社区确实拥有网络所能提供的最好的东西。他们发现了一个巨大的软件模块库，一个叫做CPAN的银行，这些系统管理员都很喜欢它。它给Perl提供了更多的灵活性，许多人都可以部署由几个超级编程大师编写的代码。


**12:15** - _Mike Bursell_

它有很多库可以做你想做的事情，如果你找不到你想要的库，你可以去提问，然后就会有好心人写出你想要的库的。

**12:21** - _Saron Yitbarek_

Mike Bursell是红帽公司的首席安全架构师。


**12:28** - _Saron Yitbarek_

正是由于Perl的自由开源，它受到不断增长的模块库的支持，它是可移植的，而且它有一个蓬勃发展的社区。事情看起来不错。Perl可以充分利用上世纪90年代互联网发展中的所有优势，但就在90年代即将结束时互联网的发展前景又一次发生了变化，时代来了一个大的转变。


**12:57** - _Alan Greenspan_

但我们又能如何知道非理性繁荣何时已过度推高了资产价值，进而导致了意料之外的长期经济收缩?


**13:12** - _Saron Yitbarek_

“非理性繁荣”是时任美联储主席Alan Greenspan在1996年对美国企业研究所说的话。他那句“非理性繁荣”是对90年代人人都经历过的网络泡沫的警告。所有早期使用Perl的网络开发人员都在那个泡沫中乘风破浪，但正如Greenspan预测的那样，泡沫在2000年破裂了。

**14:11** - _Conor Myhrvold_

大家好，我是Conor Myhrvold。在过去的五六年里我一直在编程，现在我在技术领域为Uber工作。

**14:20** - _Saron Yitbarek_

2000年代初当Conor还在高中的时候，Perl仍然是一个非常重要的东西。但他越来越意识到一种与之竞争的语言，叫做Python。


**14:31** - _Conor Myhrvold_

Python所追求的是一种更结构化的语言，用一种明显的方式来做很多不同的事情。Python就是那样设置的，而Perl做某件事有不止一种方法，这使得很多初学者都很困惑。


**14:49** - _Saron Yitbarek_

Perl有这样一句座右铭“实现它的方法不止一种。” 而Python的理念实际上是相反的，Python为每个问题都提供了一个明显的解决方案，这意味着查看别人的Python代码很容易；而另一方面查看其他人的Perl代码可能会令人困惑。Perl作为一个程序员的第三或第四种语言是有意义的，而正是因为它是一种脚本语言，而脚本是互联网管道连结的基础。


**15:23** - _Saron Yitbarek_

但是Python是一种你可以真正深入研究的语言，即使你是一个新手。Perl有一组特定的优势，比如在搜索文本和生物信息学上。但是Python就是这样一种简单通用的语言。作为人们首先想学的语言，Python获得了越来越多的信任。这是一件大事。


**15:47** - _Conor Myhrvold_

越来越多的人开始上网，越来越多的人开始学习如何编程。尤其是在这个时期相对于Perl而言，Python从中受益的是Python相对容易学习，因为它更结构化。因此就像在一个增长很快的果馅饼里，如果你能得到更多增长的果馅饼，那将最终意味着有更多的教程和更多的东西可供你使用。


**16:10** - _Saron Yitbarek_

在之前提到过的CPAN，它是Perl用户可以使用的强大的中央存储库。这在90年代是一个主要的侧重点，但CPAN的重要性也在变化。


**16:24** - _Conor Myhrvold_

这也不能真正帮助你学习一门语言，因为你是在“复制”，只是用最少的方式替换你需要的东西。从长远来看这是一个劣势，因为如果你让人们通过自己进行原始开发来学习如何使用一种编程语言，即使这需要花费更长的时间他们也会觉得自己对它投入了更多，而且他们了解在这中间发生了什么。


**16:48** - _Saron Yitbarek_

Python没有像CPAN那样的集中式存储库，但是对于那些在新千年时代来到这里的开发人员来说，在一个互联网搜索功能强大得多的世界里存储库并没有那么大的价值。


**17:05** - _Saron Yitbarek_

所以最终Python在网络上有了大量的教程，当然现在也有了像GitHub这样的平台。


**17:13** - _Conor Myhrvold_

最终发生的事情是Perl拥有的许多优势是来自一个已经过时的时代的网络效应。


**17:24** - _Saron Yitbarek_

Conor Myhrvold是Uber的一名工程师。


**17:30** - _Saron Yitbarek_

然而语言的兴衰很少是由外部力量单独决定的，而Perl的内部问题是在它的发展过程中它似乎遇到了障碍。Python正在以一种相当有序的方式发布新的迭代，而正如我们在本季度第一集中所了解到的，Perl在2000年互联网泡沫破裂之时，Python开始获得更多新开发人员的青睐。


**17:59** - _Saron Yitbarek_

每个人都期待着Perl 6的发布，人们都很兴奋。他们等啊，等啊，等啊……他们等了14年。


**18:15** - _Elizabeth Mattijsen_

人们提出了大约300多件Perl 6应该能够完成的事情，当然其中很多事情基本上是相互排斥的。


**18:26** - _Saron Yitbarek_

这是Elizabeth Mattijsen，她是Perl 6的核心开发人员。伊丽莎白在2000年参加了蒙特雷的Perl会议。那时开发者认为他们已经停滞不前了，所以Perl 6是必要的。Larry Wall同意了，但是如果说Perl 5是他对Perl的重写，那么他希望Perl 6是由社区来对Perl进行重写。由于团队合作可能需要更长时间，甚至14年，这对于那些开发者来说这是一条漫长而艰难的道路。


**19:01** - _Elizabeth Mattijsen_

我们可以说当前实施的Perl 6项目实际上是实现它的第三次尝试。


**19:07** - _Saron Yitbarek_

按照Elizabeth的说法，在这14年里有过多次尝试。中间经历了漫长而痛苦的深度的尝试。开发者们心力交瘁;人们陷入了死胡同。到2015年圣诞节那天Perl 6终于问世时，世界上的许多地方已经开始了新的发展。而需要注意的是Perl 6并没有升级为一些革命性的新东西，从而实现对Python的反击。Perl 6是对原始版本进行了深思熟虑的重新设计。


**19:43** - _Elizabeth Mattijsen_

我认为Larry Wall 在他的演讲中使用了一个很好的比喻。对他来说，Perl 5就像霍比特人，而Perl 6就像指环王。如果你仔细看《霍比特人》和《指环王》的故事，你会发现它们基本上是同一个故事。只是《霍比特人》比《指环王》小得多，有更多的情节漏洞，没有《指环王》那么宏大的背景。我认为这很好地描述了Perl 5和Perl 6之间的区别。它基本上是同样的想法，同样的心态，同样的环境，只是对它的重新构想。


**20:26** - _Saron Yitbarek_

Elizabeth Mattijsen是Perl 6的核心贡献者。


**20:32** - _Saron Yitbarek_

现在Perl甚至可能不在前20种语言之列。在外部竞争和内部延迟之间，它并没有向大多数新开发人员证明自己。但这提出了一个大问题，我们真的应该根据一种语言的受欢迎程度来判断我们的编程语言吗?或者说我们应该根据其他方面来判断一种编程语言的价值?当昔日的超级巨星成为现在的密友时，这到底意味着什么呢?


**21:06** - _Saron Yitbarek_

在世纪之交时互联网泡沫破裂，Perl的统治地位开始衰退时，Larry Wall发表了一个有趣的声明。他认为尽管Perl永远不会再成为世界上最流行的编程语言，但它可以成为较小类别中的领先者。Larry Wall说那才是真正的目标。成为同类中最好的，而不是世界上最好的。正如他所说的SUV永远比不上赛车。


**21:38** - _Saron Yitbarek_

我想深入研究这个想法，我想了解在类别中做到最好才是对编程语言的真正含义。


**21:48** - _John Siracusa_

我是John Siracusa，我是一个程序员，也是一个播客。


**21:53** - _Saron Yitbarek_

John实际上共同主持了三个播客：《意外技术播客》，《可调和的差异》和《是机器人还是？》。我们聊到了Perl在当今世界的地位。


**22:06** - _Saron Yitbarek_

Perl在当今世界排名怎么样了?它仍然是最好的计算机语言吗?


**22:10** - _John Siracusa_

Perl 6具有其他语言没有的、其他语言应该具有的东西，我一直在等待其他语言窃取它的东西。例如语法是概念化常见任务的一种好方法，而在我看来使用语法解决解析问题比使用现有的工具更令人愉快、更干净、更好。


**22:31** - _John Siracusa_

在Perl中对象系统的许多部分看起来很琐碎，但我完全希望其他语言最终能够采用，就像许多语言最终采纳了Perl 5中的许多思想一样。因此我认为Perl 6在许多类别中都是最好的。遗憾的是很少有人会发现自己有机会使用它。


**22:52** - _Saron Yitbarek_

您认为Perl 6社区的发展需要做些什么?想让人们更多地参与到Perl 6中，需要做些什么?


**23:00** - _John Siracusa_

这有点像Perl 6的故事，就像它一直在寻找一个真正奇妙的实现一样。这是第二体系问题的一部分……我认为他们称呼它为第二系统综合症……

**23:11** - _Saron Yitbarek_

唔.

**23:12** - _John Siracusa_

在Perl 6中人们希望修复世界上的所有问题。他们想要解决的一个问题是运行时的环境。是什么在运行我们的代码?运行Perl 5和之前的Perl 4的东西是一个巨大的C程序，这是由具有非常特殊的编码风格的开发者和大量宏来编写的，这是相当难以理解的。


**23:33** - _John Siracusa_

Perl 6的思想是让我们不要再那样做了，让我们不要制造大量的C代码。相反，让我们使用一个虚拟机，这是当时的时尚，有很多关于如何实现它的伟大想法。最终我们得到了几个中等到合格的虚拟机版本，这些版本有时会相互竞争，但没有一个达到真正交付语言使用时需要的性能、稳定性和特性。


**24:01** - _Saron Yitbarek_

现如今Perl到底发生了什么?你对此有什么看法?


**24:06** - _John Siracusa_

显然Perl 5似乎正在走下坡路，因为与Perl 5同时代的所有其他语言都采纳了它的大多数最佳思想，并获得了更多的支持。也就是说因为它在很长一段时间内都是王者，所以有很多Perl 5代码在运行一些大型的、重要的站点，人们需要维护和扩展这些代码。


**24:29** - _John Siracusa_

这需要很长时间才能消失。只要看看现今仍然存在的COBOL，人们仍需要然雇佣人来在COBOL上做维护的，对吗?


**24:35** - _Saron Yitbarek_

嗯哼。这是真的。


**24:36** - _John Siracusa_

你刚才问Perl是不是一种垂死的语言，我提到了COBOL，这听起来不太好。因为Perl 6本身会成为主导语言吗?看起来可能性不大。现在对其他语言有非常多的关注，如果Perl 6现在还没有得到开发者的关注，我不知道将会需要发生什么变化来让它流行起来。


**24:54** - _Saron Yitbarek_

如果按照您的方式，您对Perl的希望是什么?您希望在Perl 5或Perl 6中看到什么，以及希望看到将来发生什么?


**25:04** - _John Siracusa_

我对Perl 5的希望是人们不会忽视它，因为尽管有其他更流行的语言，但今天仍然存在采用Perl 5是最佳解决方案的事。通常这些都是胶水类型语言的问题。如果您发现自己曾经编写过shell脚本，并且您可能会说:“好吧，我不会用我的‘真正的编程语言’来做这件事。”不管是Python，还是Ruby，还是别的什么。但是shell脚本可以让我把一堆东西连接起来（胶水类型语言）。Perl是完成这项工作的更好工具。编写正确的Perl脚本要比编写正确的shell脚本更容易。


**25:40** - _Saron Yitbarek_

我认为归根结底Perl可能不再是一个适合入门的语言，但对于经验更丰富的多语言开发人员来说你永远不希望扔掉工具箱中的小工具，而且特定的工具有时使你更有境界的提升。

**25:58** - _John Siracusa_

有时我为Perl 6感到难过和沮丧，认为它不会有任何进展，有时我想“您知道吗?这是个不错的小社区”。每个社区都不需要称霸世界，也不需要成为整个行业的主导语言。实际上你就可以这样，这就是开源和编程语言的伟大之处。没人能阻止你，你可以像以前一样继续在Perl 6上工作。


**26:27** - _Saron Yitbarek_

John Siracusa是一名程序员，也是三个科技播客的共同主持人。


**26:34** - _Saron Yitbarek_

语言都有生命周期。当新的语言出现时它们能够精确地适应新的现实，像Perl这样的选择可能会占据更小、更小的领域，但这并不是一件坏事。我们的语言应该随着我们需求的变化而扩大或缩小它们的群体。在互联网开发的早期历史中，Perl是一个至关重要的角色，它以各种方式与我们联系在一起，只要看一看它的历史就会发现它的存在。


**27:11** - _Saron Yitbarek_

下次在命令行英雄中，我们将讨论：是什么将一种语言变成了一种标准?以及在基于云的开发世界中一种新标准将如何出现?


**27:26** - _Saron Yitbarek_

命令行英雄是红帽原创播客。如果你想深入了解Perl的故事，或者任何我们在第三季中探索的编程语言，请访问 [redhat.com/commandlineheroes](//redhat.com/commandlineheroes) 。我们的网站里有许多精彩内容等你去探索。


**27:49** - _Saron Yitbarek_

我是Saron Yitbarek。下节课让我们继续谈编码人生。


--------------------------------------------------------------------------------

via: https://www.redhat.com/en/command-line-heroes/season-3/diving-for-perl

作者：[Red Hat][a]
选题：[bestony][b]
译者：[Mikedkmilk](https://github.com/Mikedkmilk)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCRH](https://github.com/LCTT/LCRH) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出
[a]: https://www.redhat.com/en/command-line-heroes
[b]: https://github.com/bestony