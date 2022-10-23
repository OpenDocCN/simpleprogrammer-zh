# Web 开发原则:前端与后端

> 原文：<https://simpleprogrammer.com/front-end-vs-back-end/>

尽管看起来很难，但是很多程序员不知道前端和后端开发之间的区别。我不怪他们。其实这样也可以。

因此，在这个视频中，我将更多地解释前端和后端开发的区别。这两个软件开发领域的主要区别是什么？

前端开发是用户交互的部分。当你在互联网上浏览时，你所看到的一切，从字体和颜色到下拉菜单和滑块，都是由电脑浏览器控制的 HTML、CSS 和 JavaScript 的组合。后端由服务器、应用程序和数据库组成。后端开发人员构建和维护支持这些组件的技术，这些组件共同使网站面向用户的一面能够首先存在。

所以，想知道更多关于这两者之间的区别吗？观看此视频，了解详情！

<center>

[https://www.youtube.com/embed/hAjGmZfsh50](https://www.youtube.com/embed/hAjGmZfsh50)

**Transcript Of The Video**

**约翰不结束**

约翰:嘿，你好，来自 simpleprogrammer.com[的约翰·桑梅兹](https://simpleprogrammer.com)。我要检查一下我的麦克风和电池。我想我会回答这个问题。我刚刚在写我新书的一些章节。我正在写一本关于——叫做——暂定名为《软件开发人员完整职业指南》的书，我在里面谈到了前端和后端，所以我看了看，发现了这个问题。我想，“啊，这太完美了。我只回答这个问题，因为我一直在写这个话题，“老实说，我觉得有点无聊。我喜欢做更固执己见的事情，但是，是的。我在这本书的这一部分，我正在定义一些东西，谈论一些我并不真正超级热衷的东西，但你必须熬过它，对吗？我想至少给它带来一些幽默。这将使它更有娱乐性，但这是你必须知道的东西。如果不给你所有你需要知道的东西，我就不能写一本关于软件开发人员指南或完整职业指南的书。

在我们开始之前，我想花点时间感谢 hire.com 赞助了 Simple Programmer。他们很棒。我和很多想赞助简单程序员在 YouTube 视频中出现的公司相处不好，但我这么做了，因为我喜欢他们做的事情。我喜欢他们的哲学。我喜欢他们工作的方式。我真的很喜欢这个翻转求职的想法。你可以自己去看看。去 hire.com/simpleprogrammer.你还会得到奖金。通常当你通过他们找到工作时，他们会给你 1000 美元。如果你通过那个链接，他们会给你 2。看看这个。你自己看吧。这是一种完全不同的求职方式。我绝对推荐。顺便让我知道你和他们的经历。我很想听听大家的意见。

让我们来谈谈新程序员的前端和后端。这封邮件说，“嗨，约翰，我一周前才发现你的视频，我真的觉得你的频道很有用。也许你能帮我解决一个难题？我对编码很感兴趣已经有一段时间了，像硅谷这样的展会把我推向了这个方向。”我没看过那个节目，但是我听说它很有趣。我不看电视。“我想知道对于一个程序员来说，是专攻前端还是后端编程更好，还是两者都懂一点。我并没有真正理解其中的区别，我在 Python 和 HTML 之间切换了一段时间，只是为了重新开始使用 HTML。我想知道，特别是随着 Wix 和 Squarespace 等网站的兴起，对前端开发人员有什么需求吗？我应该跳回 Python 还是继续我的道路，并检查我职业生涯的后端层？非常感谢，约翰。”

关于什么是前端和后端存在混淆。我有它的定义。对我来说，前端开发是在用户界面和 UI 类型的代码上工作，后端是用户看不到的任何东西，无论它是什么，发生了什么，在某人点击按钮后发生的业务逻辑，提交表单，所有与数据库连接的东西。所有我认为后端。

不同的人会说，“哦，前端工作就是做 HTML、CSS 和 JavaScript。”嗯，_ _ _ _ _ _ _[听不清 00:03:18]的工作，但只是创建页面的设计。我称之为网页设计。我不知道。有这么多的术语，这么多的混乱，但对我来说，前端就像我说的，它创建网页和它的视觉元素和一些编程。用户界面中的逻辑与应用程序的业务逻辑无关。对我来说，这是我的底线。

你应该做什么，你需要知道一点这两者吗？当然，这两者你都需要知道一点，对吗？你不可能不知道后端开发，对不对？我的意思是，你打算做什么，只是创建用户界面？我想你可以。后端的东西是真正的编程发生的地方，如果你像商业逻辑，算法之类的东西来考虑它。前端不应该有太多的逻辑。会有一些事情变得有些模糊，因为我们现在有 JavaScript 框架，我们可以从数据库中提取数据，或者我们可以喜欢——我们有更复杂的东西和一些连接代码，甚至在前端有 MVC 类型的代码。我们在前端有一些业务逻辑和应用程序流类型的连线和代码，这样可以让事情完成得更好一些。这有点模糊了界限，而我认为之前我们有 HTML、CSS 和一点 JavaScript，然后有服务器端渲染，这是非常清楚的。服务器端渲染我们可以称之为后端，我们可以调用 HTML 并填充前端。

即使在这一点上，我也会将服务器端呈现部分称为前端，我会划清界限，说:“好吧，当你真正进入业务逻辑时，现在你在后端。”不管怎样，这没什么大不了的。我想说的是，拥有这两种技能，知道如何正确地做这件事，因为我认为对一个软件开发者来说真正有价值的是，你需要能够从头到尾自己创建一个应用程序。这意味着您需要能够创建用户界面。你要知道 HTML，CSS，JavaScript。你需要知道一些服务器端的语言——可以是 Python，可以是 ASP.NET，C#框架，任何你想要的。可能是 node。然后，你需要能够连接到数据库，获得数据，插入数据，因为如果你有这些基本知识，那么你真的很有用。

现在，又有人会说，“等一下，John，你是说成为一个全栈开发者吗？你是说不要搞特殊化？”不。我是说你不会成为所有这些领域的专家，但是你必须有实用的知识。如果你能构建一个应用程序，这是一个有价值的技能，因为你不会被卡住。你将能够融入并帮助理解系统中正在发生的事情。作为一名软件开发人员，很多时候问题发生在上游，必须追溯到下游。如果你说，“好吧，我对数据库一无所知”，那么你在团队中就不会很有用。你不能只是举手说，“哦，我不碰数据库的东西。我是一名前端开发人员。我不碰任何后端的东西。”你就没什么用了。你明白我在说什么吗？

我会——挑你想要的。你可以专攻。如果你不是特别擅长设计，我做了一个关于你必须是一个设计师才能做开发的视频。我做过一些这方面的视频。如果你不是特别擅长设计，你不喜欢设计和前端，这可能会有点痛苦。你也许能破解代码，除了你会像我一样看着你创造的东西，你会说，“那看起来像狗屎。”我做前端开发的时候就是这么做的，所以我更喜欢后端开发。

我可以编写一个算法，并找出如何设计架构，系统的后端，并制作整个框架之类的东西。我喜欢这样。这有点像——决定你想做什么，专攻其中一个领域。从中挑选一个专业。不仅仅是你的结构不能成为前端或后端，而是你想选择一些细分的东西。你应该能够做到——你应该有这个能力。

如果我必须选一个，如果你说，“嗯，什么最有价值？”我会说前端，只是因为有更多的工作需要你去创造一些面向用户的东西，网页之类的东西，即使你不能设计它，但你可以连接并理解它，特别是 web 2.0，JavaScript 框架和所有这些东西。

无论如何，我希望这对你有所帮助。这绝对是一个前端和后端混淆的话题。就像我说的，我不认为这很有趣。你只想写代码。你想成为一个有用的能写应用程序的人。要做到这一点，你必须对两者都有所了解，但你可能会选择一个你主要关注和花费时间的地方。对，就是这样。

如果你喜欢这个视频，请订阅该频道。如果您想加入简单的程序员社区并支持该频道，请查看赞助人页面。那里有一些非常酷的东西，一些非常酷的奖励，我真的没有充分谈论脸书小组，但我们有一个很棒的脸书小组，在那里我们有简单的程序员社区，他们一起回答问题，相互交谈，与我交谈，我在那里很活跃。如果你想加入的话，老实说，进去是相当便宜的。它支持社区，支持渠道，你成为其中的一员。

反正就是这样。同样，如果你喜欢这个视频，就订阅吧。下次再聊。保重。

</center>