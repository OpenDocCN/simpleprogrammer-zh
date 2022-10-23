# 新项目的错误跟踪:我真正需要什么？

> 原文：<https://simpleprogrammer.com/error-tracking-new-projects/>

当我开始一个新的软件项目时，我记得我被如何让我的应用程序成功所淹没。我想知道人们是否会喜欢这个产品，更不用说付钱了。

我很幸运，凭借我在一家大型公司担任软件开发人员的经验，我可以将从以前的项目中学到的许多知识用于我的个人项目，包括我需要使用哪些工具来立即投入工作。

我很快发现错误跟踪是最重要的工具之一。(在本文中，我将交替使用术语“错误”和“bug ”,但我指的是同一件事。)

错误跟踪软件会自动对你的软件触发的错误和崩溃进行分类，这是必要的，这样你就可以发布好的、没有错误的软件——我们都认为这是生产的圣杯。您可能还会听说[错误跟踪工具](https://raygun.com/platform/crash-reporting)被称为错误监控或崩溃报告工具。

你需要在项目中尽可能早地开始错误跟踪，而不是等到几年后，这是因为在宝贵的启动阶段，你需要收集尽可能多的关于应用程序状态的反馈，以便你能够根据你和你的客户的需求来调整、调整、优先化和发展。

为了让您从我花在研究管理错误跟踪的最佳方法上的时间中受益，我将与您分享几个在我的开发职业生涯之初就出现在我脑海中的问题:

*   为什么我甚至需要错误跟踪？
*   我需要购买一个错误跟踪工具还是可以自己构建一个？
*   一旦我有了一个错误跟踪工具，我应该如何使用它提供的度量来确保高质量的软件？

下面我来继续回答这些问题。

## 为什么我需要错误跟踪？

![](img/d16bad6091fc7b56427dd054cb290dbf.png)

在发布之前，你可能会埋头于代码库，专注于发布日期。但是决定你成功的是最终产品的质量，而不是你制造产品的速度。

错误跟踪会在生产中暴露错误，让您有机会修复它们，并确保它们永远不会落入用户手中，这是确保您的项目尽可能高质量的重要部分。

你可能已经花了几个小时在不同的环境中测试你的软件，但是错误是软件生命中很自然的一部分——不管你是微软还是一个试图在游戏世界中成功的独立开发者。用户总会找到奇怪的导航方式，版本发布会引入看不见的错误，第三方脚本会导致性能问题。

虽然您无法阻止所有的 bug，但是您可以通过尽早检测到它们并快速解决它们来最大限度地降低严重损害的风险。但是你不可能一下子无处不在，这就是错误跟踪可以解决的问题。

错误跟踪将自动执行最耗时的任务(寻找问题)，因此您最有价值的资产(您)可以将时间花在为您的应用程序提供价值的决策任务上(如编码软件)。

请记住，缓慢和有缺陷的软件不是一个选项。

## 我应该建造还是购买？

构建还是购买是我一开始问的问题。这是一个常见的问题，尤其是当你第一次寻找工具来支持你的项目的时候。如果你和我一样，你可能资源匮乏——时间和金钱都很少——所以你想要项目的最佳选择*和*你自己的理智。

所以你必须做出选择。作为一名企业家，你可能会有一种“如果你想把工作做好，就自己做”的心态。但是不要忘记另一面——认识到你是最有价值的资产，你不应该把时间花在对企业没有价值的琐碎任务上。

一个忙碌却贫穷的开发人员该做些什么呢？以下是双方的一些平衡论点；最终，你必须做出对你最有利的选择。

### 何时构建

**具体要求**

现成的软件可能无法让你像自己希望的那样灵活；例如，您可能会发现自己需要定制的特性来允许特定行业的集成相互通信。大多数软件都是根据大多数人的需求构建的。如果您以特殊方式超出了该区域，您可能需要评估自定义构建。

**复杂集成**

如果您有复杂的集成，您不希望沟通问题影响您未来的团队。如果您的集成会因为外部工具而停止，那么构建您自己的错误跟踪系统。

**你真的别无选择**

有总比没有好。如果你手头拮据，像 Google Analytics 这样的免费工具或者像 elmah.io 这样的错误记录工具在这个阶段可能是合适的。

### 什么时候买

![](img/e96d5fb7cfee107e8d9834a37f5d0317.png)

**缺乏开发者资源**

如果你的开发团队时间紧张，你就不应该开发软件。你的首要任务是让你的用户对你的应用有一个很好的体验，尤其是当它还不到两年的时候。你会有很多问题需要解决，你得到的帮助越多越好。

**时间不够**

创作只是故事的一部分——你将花费大部分时间来维护和改进你的史诗代码库的设计，希望在未来很多年都是如此。马丁·福勒有一本关于这个主题的优秀书籍。

**缺乏专业技术知识**

你有制造内部工具的经验吗？如果存在技能差距，你可能会让你的团队遭受失败和挫折——当你可以为你的客户群创建功能时，这些都是浪费时间。

**需要更多细节**

如果您构建了一个允许您跟踪错误的工具，那么如果不做大量艰苦的工作，您可能无法获得如此详细的信息。例如，要快速诊断一个错误，您需要堆栈跟踪和错误发生的确切环境。

## 那么，我应该用什么来衡量优秀的应用性能呢？

错误跟踪工具不仅仅是在粒度级别上管理软件错误。您可以使用它们提供的度量标准来为您的最终用户设置软件性能的基准。

当然，像有多少人采用你的应用程序这样的指标真的很重要，应该加以衡量，但它们一直在变化。而且，随着我们行业的成熟，人们对优秀软件的期望也越来越高。

要想在软件市场上有机会，您的软件至少需要:

*   保持高质量，这样你的应用就不会崩溃
*   在许多不同的环境中快速加载(三秒钟以下是理想状态)
*   拥有可重复和可扩展的交付流程
*   让用户享受用于预期目的的软件

听起来很多，对吧？

嗯，在从我自己的项目中获得许多学习经验，并在一个更大的团队中工作后，我发现你可以使用四个指标来准确描述你的应用程序的性能。使用您的错误跟踪工具每天报告这些度量标准，您将开始构建能够为您的用户提供更好体验的软件。

**受 bug 影响的用户**

忘记错误计数。如果 10，000 个错误影响一个客户，这还不如 500 个错误影响 250 个客户糟糕。在我的团队中，我们每个月都会评估受影响的客户，我们的目标是减少受影响的客户数量。

**平均应用程序响应时间**

更好的性能会赚钱，跟踪的最好方法是测量平均响应时间，也就是 50%的客户所经历的。

**P99 应用程序响应时间**

P99 对于理解应用程序响应时间的上限非常重要。这是一个指标，指的是第 99%的用户加载应用程序所需的时间。这通常会超过三秒，但如果你的应用程序需要 25 秒才能加载，你就要开始担心了。我使用第 99 个百分点，而不是第 100 个百分点，因为第 100 个百分点通常代表超时和机器人。

**解决的错误比产生的错误多**

测量 bug 计数，而不是跟踪崩溃计数。作为一个指南，你应该解决比你创造的更多的错误，在一个棕色地带项目(一个解决问题空间的项目，比如替换遗留系统)，可能更多。

关注这四个指标将会:

*   通过更少的崩溃和更快的软件改善[用户体验](https://simpleprogrammer.com/2017/08/04/developing-long-term-iot-users/)
*   减少技术债务的积累(确保你没有在每一次发布后留下破坏的痕迹)

随着你使用错误跟踪软件在应用程序发布后收集更多数据，你将开始构建一个如何引导你的应用程序成功的图景，以及在哪里集中资源以获得最大效果。

## 开始使用错误跟踪

错误跟踪可以提供安全和安心，让您的早期客户获得最佳的应用体验，同时您可以专注于构建新功能的重要工作。

从一开始就跟踪你的错误，这样你就可以在事情发生的时候修复它们，而不是让它们随着时间的推移而积累。在你决定构建自己的错误跟踪软件或购买现成的东西时，要考虑所有的因素。请记住，受 bug 影响的用户只是您应该在应用程序的整个生命周期中跟踪的一个指标。

错误和崩溃是必然会发生的，但是如果您跟踪它们并快速修复它们，您的客户将会有很好的体验，同时您可以将资源集中在最重要的事情上。这是双赢！

## 那么，我应该使用哪些工具来确保我的软件项目从一开始就成功呢？

![](img/e7c824a90fdc18bebad26baecc7257b0.png)

在你项目的这个[早期阶段，你可能会有一个紧张的预算。但是错误跟踪只是您需要担心的事情之一。如果你要构建一个成功的应用程序，你需要一个完整的工具包的支持。正确的工具对你的成长至关重要，因为它们会挑起重担。](http://www.amazon.com/exec/obidos/ASIN/0201633612/makithecompsi-20)

在这个行业工作了五年之后，我有幸照顾了成千上万的开发人员和他们的软件性能，所以我只是把这些工具传递下去。

Kunal Johar 向我推荐了这个列表，他是一家成功的技术公司的联合创始人，也是许多年轻软件项目的导师。如果你真的想给顾客带来好的体验，这是你最起码需要的。

*   [吉拉软件](https://www.atlassian.com/software/jira)——用于项目管理
*   [GitHub](https://github.com/)–存储库管理
*   [松弛](https://slack.com/)–团队沟通和快速提出问题
*   [对讲](https://www.intercom.com/)——客服管理平台
*   [Stripe.com](https://stripe.com/)–接收和组织付款
*   [射线枪](https://raygun.com/)–用于崩溃和错误跟踪

就是这样！关于这个列表的事情是他们都互相集成，总是谈论和提供关于你的软件质量的反馈。

是的，其中一些工具确实有现金投资。但是你的软件项目应该成功。大多数公司都有创业计划，可以随着你的成长而扩展。管理用户期望、提供卓越的客户体验以及监控应用程序的性能问题从未如此简单。