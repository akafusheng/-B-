# A-Comprehensive-Guide-To-Business-Product-Design 

# B端产品设计指南



### 界面设计流程

> 1. 产品经理绘制线框图原型，表达软件中每个页面的设计需求。
> 2. UE设计师协助产品经理完成交互体验，并制作交互原型。
> 3. UI设计师基于交互原型进行美工设计，生成切图文件。
> 4. 前端工程师拿到切图文件，进行前端开发，包括实现交互、动效等。



### 原型图绘制

产品经理需要将每个页面的排版样式、控件设计及交互效果，用通俗易懂的形式表达出来，以方便其他同事快速理解。线框图（也叫原型图）是一种很好的表现形式。绘制线框图的工具有很多，常见的有[Axure](https://www.axure.com/)、[Mockplus](https://www.mockplus.com/)、[墨刀](https://modao.cc/)、[Visio](https://support.microsoft.com/en-us/office/install-visio-or-access-visio-for-the-web-f98f21e3-aa02-4827-9167-ddab5b025710)等。

**线框图的重点在于说清楚界面上的交互功能设计，而非UI效果**。



使用 Axure 绘制原型图：[开始使用 Axure RP ·Axure Docs](https://docs.axure.com/axure-rp/reference/getting-started-video/)



### 尼尔森十大可用性原则

线框图需要反映出交互功能，因而在绘制的过程中需要考虑：用户在 这个页面上会进行哪些交互、怎样设计能达到最好的交互效果。大多数情况下，B端产品经理还是需要自己完成交互设计的。因此，产品 经理有必要投入精力来**学习和练习交互设计**。



#### 反馈原则(Visibility of system status)

系统应该在合理的时间、用正确的方式，向用户提示或反馈目前系统 在做什么、发生了什么。

人机交互的基本原则是，让系统和用户之间保持良好的沟通和信息传 递。系统要告知用户发生了什么，预期是什么，如果系统不能及时向用户 反馈合适的信息，用户必然会感到失控和焦虑，不知道下一步要做什么。

以下是遵循反馈原则的一些常见设计案例:

- 安装程序时显示进度条，并预估还需要多久结束
- 上传文件时显示进度条，并提示预估剩余时间
- 提交表单时，如果校验失败，则在填写有误的内容旁边提示错误原因
- 程序未响应时，系统会让用户选择是关闭程序还是等待程序响应



#### 隐喻原则(Match between system and the real world)

系统要采用用户熟悉的语句、短语、符号来表达意思。遵循真实世界 的认知、习惯，让信息的呈现更加自然，易于辨识和接受。

在人机交互设计中，程序的沟通和表达、功能的呈现，都要用最自然 的、用户容易理解的方式，避免采用计算机程序语言的表达方式。设计时 要采用符合真实世界认知的方式，让用户通过联想、类比等方法轻松地理 解程序想表达的含义。



#### 回退原则（User control and freedom）

用户经常会不小心操作错误，需要有一个简单的功能，让程序迅速恢 复到错误发生之前的状态。

用户误操作的概率极高。对于误操作，软件系统应该尽量提供“撤 销”“重做”或“反悔”的功能，让系统迅速返回错误发生之前的状态。当然， 不是所有操作都是可以“反悔”的，比如，你可以撤销一笔错误的订单，但 不能撤销一笔成功的转账交易。



#### 一致原则（Consistency and standards）

同样的情景、环境下，用户进行相同的操作，结果应该一致；系统或 平台的风格、体验也应该保持一致。

软件设计、产品设计中有很多约定俗成的规范，虽然没有明文规定， 但大家都在遵守，因为用户已经习惯了这些规范。我们在进行设计时，应 该遵循惯例，并且保持系统的一致感，不要盲目地标新立异。

此外，在一个或多个系统中，要采用统一的设计风格。不论是图标的 选用，还是布局的规划，要保持整齐的一致性，这样用户容易理解，并且 容易习惯和适应。



#### 防错原则（Error prevention）

系统要避免错误发生，这好过出错后再给提示。

进行设计时，首先要考虑如何避免错误发生，其次再考虑如何检查、 校验异常。这样做一方面可以让问题更简单，另一方面可以让用户避免或 减少无谓操作。 例如，有些时候，为了防止用户重复提交或重复点击，第一次点击按 钮后就将按钮置灰，直到处理完成才恢复。

有时还会通过调整按钮顺序，避免用户误点。比如，对于很重要的操 作，为了防止用户顺手误点，会将二次确认对话框中的“是”和“否”两个按 钮对调位置。



#### 记忆原则（Recognition rather than recall）

让系统的相关信息在需要的时候显示出来，减轻用户的记忆负担。

计算机应该减轻人们的记忆负担，而不是相反。例如，当切换页面 时，不应该让用户记住不同页面的内容，而应该在合适的地方积极地呈现 或提示之前的信息。

例如，在所有的电商购物流程中，在用户提交订单后，都会出现一 个核对页面，让用户再次核对填写是否正确。这个设计非常有用，我就经 常在下单时忘了修改默认地址，再次核对时才发现。



#### 灵活易用原则（Flexibility and efficiency of use）

系统的用户中，中级用户往往最多，初级和高级用户相对较少。系统 应为大多数人设计，同时兼顾少数人的需求，做到灵活易用。

灵活易用原则不仅是一个交互设计原则，也代表了一种软件产品设计 理念：系统既要做得简单、易用，让所有中级用户用起来得心应手；也要 提供必要的帮助，让刚入门的初级用户顺利上手；还需要支持灵活的个性 化定制，让高级用户能够以进阶的方式使用系统，充分发挥其价值。

让高级用户灵活定制的最典型的例子是各类软件和App的配置功能， 基本上所有软件都会提供定制化功能，从快捷键设置，到页面布局，再到 自定义参数，软件系统会尽量提供全面的个性化设置功能，来满足不同用 户的使用诉求和习惯。



#### 简约设计原则（Aesthetic and minimalist design）

对话中不应该包含无关的或没必要的信息；增加或强化一些信息就意 味着弱化另一些信息。

重点太多，相当于没有重点。在视觉设计中，要掌握好“突出标记”的 度，以及内容的呈现方式。



#### 容错原则 （ Help users recognize ，diagnose，and recover from errors）

错误信息应该用通俗易懂的语言说明，而不是只向用户提示错误代 码；提示错误信息时要给出解决建议。

对于很多运行时错误或异常，计算机程序都会返回某个错误代码，但 是对于用户来讲，看到这些错误代码并不明白发生了什么，所以一定要将 错误代码转换成用户能看懂的语句，并告诉用户解决的建议。 访问网站时，如果页面不存在，服务器提供的标准错误提示是404错误，很多用户并不理解404是什么意思。提示信息改为："网站维护中，请稍后访问" 更好。

再例如，做得比较好的表单填写页面，对于不符合格式要求的内容会 立即进行提示，而不是等到用户提交时才去校验并提示错误；提示时除了 指出填写错误，还会说明规范的填写要求，以便用户理解错误原因并做出 修正。



#### 帮助原则（Help and documentation）

对于一个设计良好的系统，用户往往不需要经过培训就能轻松上手使 用，但是提供帮助文档依然是很有必要的。帮助信息应该易于检索，通过 明确的步骤引导用户解决问题，并且不能太复杂。

现在的软件产品，尤其是C端产品普遍做了良好的交互设计，可以帮助 用户快速学习使用，而不用阅读、理解复杂的说明文档。 然而，B端产品的复杂性比C端产品高很多，因为B端产品蕴含很多业 务流程的规则，系统中的一个按钮可能代表了一个复杂的业务处理规则， 如果不了解整个业务场景和处理规则，是很难理解按钮的操作含义的。 因此，对于B端产品，用户进行自助服务、自助操作的难度高很多，B 端产品的帮助文档依然有存在的必要。产品设计人员要尽量在前端交互上 做好引导提示，对于复杂的规则和逻辑，可以考虑通过帮助文档来指导用 户。



### 界面设计建议

只要业务建模合理，流程、角色清晰，界面设计就会很轻松。这里提 供一些B端产品界面设计的建议，供大家参考。

#### 借鉴成熟软件

网上有很多免费试用的系 统 可 供 学 习 ， 比 如 Google Analytics 、 百 度 统 计 、 管 家 婆 云 ERP 、 Udesk、SalesForce等。结合你设计的软件形态，找到行业内相似的 SaaS软件，借鉴并参考其布局、交互方式，可以提高设计效率与合理性。 产品经理要经常浏览、研究不同系统或App的交互设计方案，多看、 多用，很多基本的交互设计感觉就会潜移默化地植入脑海中，在做产品设 计时就会想起曾经见过的类似的功能设计，从而借鉴参考。

#### 善于使用模板

除了借鉴成熟的商业软件，还可以使用原型绘制工具提供的模板实现 快速设计。

#### 采用标准控件

B端产品不需要花哨的前端界面，不需要充满创意的控件。很多产品新 人喜欢在界面设计或交互设计上做太多的创新，实际上大可不必，因为B端 产品的用户需要的是解决业务问题、提高效率，交互体验并不是他们最在 意的，而且复杂的界面和交互设计会增加研发的工作量。

选用标准的控件方案可以节约产品经理和前端工程师大量的时间。什 么叫标准的控件呢？Visio或Axure里提供的可以绘制的控件就是标准控 件。不必创造这些标准控件以外的控件！

还要说明一点，产品经理设计的界面存在不合理、小瑕疵是很正常的 事情，甚至在设计、验收的过程中都没有被发现，系统投入使用后才被用 户发现。因此，在系统上线后，产品经理要多去用户现场观察交流，发现 并解决问题。



### 报表设计

任何业务的开展和运转都需报表，报表是业务管理中不可缺少的工 具。

一线业务人员需要通过报表来掌握自己的工作情况，并根据需要调整 工作节奏；

一线主管需要通过报表来掌握团队的工作情况，和目标进行对 比，调整工作安排；

分公司或总部分析人员需要通过报表进行详细的数据 分析，掌握业绩情况，并输出报告；

高管需要通过报表掌握核心指标的每 日变化，以及公司整体的经营情况。

业务报表的核心价值是**掌握事实**、**发现问题、分析原因、产生对策。** 产品经理要和业务人员一起，关注完整的体系化指标建设，设计有实用价 值的报表。**观察、分析问题的视角和思路是报表设计的核心，绚丽的交互只是次要的外在。**



#### 报表设计与流程

报表设计可能非常简单，也可能非常复杂。简单的情况是，业务人员 提交了报表需求，明确了报表表样，产品经理不用思考表格设计的思路， 只需要负责实现即可；复杂的情况是，产品经理要参与业务分析工作，建 立业务分析监控体系，并负责实现线上化。

产品经理需要理解用户使用报表的方式，和用户持续沟通，不断优化报表设计。只有从用户使用报表和分析问题的角度考 虑，才能设计出优秀的报表产品。

大家平时可以多观察《华尔街日报》、上市公司财报等规范的商业文 件或报告，里面表格的呈现形式都非常讲究、专业。正是这些小细节体现 了设计人员的专业性，无论是报表设计，还是平日做分析报告，都应该留 意这些细节。



##### 报表设计的建议

报表设计是B端产品经理必须掌握的技能之一。针对报表设计，我们有 如下建议。 

**聚焦业务分析本身** 

业务分析思路才是报表设计的核心，产品经理要尽量参与分析体系构 建的过程，这是帮助自己进一步理解业务运行和管理机制的非常好的机 会，不要把太多的精力投入在交互体验设计上。 6.4.1节提到过，根据工作性质不同，产品经理在报表设计过程中的介 入程度、工作内容会有很大差别：有些情况下，产品经理要负责建立整个 分析体系；有些情况下，产品经理只需负责后续开发。不论是何种情况， 产品经理都要尽量贴近业务，即便是被动地接受报表需求，也要努力思考 其背后的设计思路。 

**不要急于线上化** 

在业务团队中，新设计的报表一般都是由数据分析团队手工制作的， 需要在实践中随时优化修改。如果着急将这类报表线上化，有可能会面临 无数次返工。 试想，在一张新的管理报表试用期间，管理人员随时可能要求调整个 别指标，或调整格式。如果是线下的，马上就可以调整完毕，但如果已经 在系统中上线，就涉及开发、调试、上线，不能很快响应，影响工作。 等新的报表在线下试用的过程中调试好各种问题后，再实现线上化， 是一个更好的选择。 

**上线后不要急于推广** 

报表研发面临的典型困难和挑战是对数据准确性的验证测试问题，尤 其是比较复杂的数据指标，运算过程复杂，验证测试困难： · 如果是线下已有指标，则需要将线上系统计算的结果和线下计算的 数据对比，如果发现不同，分析其中的原因，但并不能认为线下手工计算 的、长期使用的数据就一定是正确的。 · 如果是线下没有的指标，测试工作就更加麻烦，只能非常谨慎小心 地手工模拟核算，再和系统计算的结果对比，需要足够的细心和耐心。 鉴于此，报表上线后，应该谨慎、小心地进行一段时间的并行验证， 即将线上系统的计算数据和线下手工计算的数据进行核对、验证。确定线 上系统的计算数据准确无误后，再进行全面推广。否则，如果线上系统计 算出来的是错误数据，会导致业务决策出错。 

**理解掌握数据仓库原理**

 想要完成高阶的报表设计，以及针对企业整体经营分析的报表设计， 需要进入一个更加专业的领域，即数据仓库领域。 从企业的视角来看，广义的“报表”设计是一个非常庞大的体系化工 程。如何保证各个业务团队看到的都是同样口径的准确数据？如何保证不 同团队的人对同一份数据有同样的理解、在同一个频道对话？如何保证企 业数据得到“治理”，数据管理井井有条？如何保证软件工程能够提供灵活 的数据和工具，让分析团队能够快速高效、随时随地分析数据？ 要解决这些问题，需要专业的技术人才运用专业工具进行企业级数 据、报表体系设计，构建一套合理的企业级数据、报表平台，这就要用到 数据仓库的知识。这是一个业务和技术高度交融的方向，产品人员必须同 时具备技术架构知识及业务知识，才能正确开展设计工作。 B端产品经理需要了解数据仓库的基本概念，包括掌握数据体系的逻辑 架构，理解数据集市、星形模型、数据立方体等基础概念，这对报表设计 十分有帮助。 

【资源推荐】 

学习数据仓库知识，推荐阅读韩家玮教授的经典著作《数据挖掘概念与技术》，其中前3章详细讲述了数据仓库、数据集市、数据处理的基础知 识，值得每一位产品经理阅读。这本书的其余部分讲述的是数据挖掘算 法，如果你从事的是策略算法相关工作，也值得一读。



#### 数据埋点

数据埋点设计是产品交互设计过程中必须同时进行的工作，数据埋点 无论是对C端产品还是对B端产品来说都很重要：对于C端产品来讲，通过数据埋点可以**分析用户行为**，**持续优化产品**，如果没有数据埋点，C端产品 运营就无从下手；对于B端产品来讲，数据埋点是考核产品使用程度的一个 重要依据，也是业务用户行为分析、产品分析、产品改善的重要参考数据来源。



##### 什么是数据埋点

在Web 1.0时代，网站设计人员及分析人员需要了解网站的访客数 量、访客来源、页面访问情况等信息，从而优化网站结构和内容。例如， 分析人员需要知道什么样的排版设计可以提高转化率，哪些版块内容比较 吸引人、应该加大投入。 为了满足这些分析诉求，程序员可以自己开发一套数据监控平台，记 录访客相关的所有数据，再开发一套报表呈现平台，让分析人员能够方便 地进行数据观察和分析。但是这样做的成本非常高，小公司根本没有实力 做这些事情。 然而，监控、分析访客的行为，研究站点的流量来源和走势，这是网 站 运 营 的 刚 需 ， 尤 其 是 在 各 类 线 上 广 告 投 放 体 系 （ 例 如 SEO 、 AdExchange）成熟之后，网站主更加需要功能强大的分析工具，帮助其 优化网站、提升网站的转化率和商业价值。 于是，各类专业的网站监控、流量分析的统计工具应运而生。知名的 网站分析软件有国内的CNZZ（后来和友盟合并）、百度统计，国际上有 Adobe的Ominiture和大名鼎鼎的Google Analytics。 使 用 这 些 分 析 工 具 的 方 法 非 常 简 单 ， 一 般 是 将 一 小 段 唯 一 的 JavaScript代码片段注入网站的一个公共JavaScript文件（或公共的HTML 代码片段）即可，工作量非常小，部署非常方便。如果需要更加精细地监 控按钮点击等行为，则需要针对每一个交互事件插入更有针对性的代码片 段。**这些在网站中注入分析工具提供的代码片段，以便网站分析工具能够准确捕捉用户行为的工作，就叫数据埋点。**移动端App的数据埋点和Web 端大同小异，也需要在App代码中“埋入”各种分析工具提供的代码片段。

数据埋点的流程一般包括**申请分析网站账号**、**获取埋点代码片段**、将 **代码片段埋入网站或App**、**观察分析数据。**

前三步一般都由研发人员负责，产品经理重点参与第四步(观察分析数据)。



##### 常见的B端埋点工具简介

目 前 国 内 使 用 比 较 多 的 Web 端 埋 点 工 具 有 [Google Analytics](https://analytics.google.com/analytics/web/provision/#/provision) （GA）、[百度统计](https://tongji.baidu.com/web/welcome/login)，移动端埋点工具有GrowingIO、诸葛IO、神策。



##### 埋点工具的数据分析

完成埋点后，埋点软件就开始采集用户访问网站或使用App的各种行 为数据了，登录埋点工具管理后台，产品经理便可以查看、监控数据，进 行各种有趣的分析，我们主要以GA为例进行介绍。GA是Google的产品， 功能极其强大，已经成为埋点分析领域的标杆，其他埋点工具或多或少都 参考了GA的设计理念。因此，只要理解GA的工作原理和使用方法，就很 容易理解并使用其他埋点工具。



#### 权限设计

权限设计是业务系统设计中一个非常重要的环 节，它反映了设计人员对整个业务体系中岗位和流程的理解。

权限设计的 前提是合理的角色设计，在此基础上，只需要明确不同角色能访问哪些页 面、能看到哪些数据以及能做什么操作即可。在界面设计完成后，就要做 相关的权限设计了。软件系统的权限包含两部分：

- **功能权限**，指各个角色可以操作的界面、按钮等，例如管理员可以 进行新增、删除、修改等操作；运营人员在同样的页面上只能使用各种筛 选条件查看数据，无法做更改。
- **数据权限**，指各个角色在各页面中能看到的数据范围，例如分公司 管理员在订单查询页能看到分公司的所有订单，而区域主管在订单查询页 只能看到所在区域的订单。



##### 功能权限设计

设计页面的功能时，要考虑页面中的各个功能点是否要做权限控制。 相应地，**在每个页面的设计文档中，除了描述页面功能本身，还需要描述系统中不同角色对页面中的各个功能点的访问权限。**我们通常用权限表来描述权限、角色的配置关系，这张表在产品设计阶段就需要准备好。

|      | 一级导航 | 页面       | 页面元素    | 管理员 | 运营人员 |
| ---- | -------- | ---------- | ----------- | ------ | -------- |
| 1    | 首页     | 首页       | -           | ✓      | ✓        |
| 2    | 客户管理 | 门店列表页 | “编辑” 按钮 | ✓      | ✓        |
| 3    | 客户管理 | 门店列表页 | “删除” 按钮 | ✓      | ✓        |



## 参考文献

[决胜B端 (豆瓣) (douban.com)](https://book.douban.com/subject/33454250/)

产品设计方法 https://www.smashingmagazine.com/2018/01/comprehensive-guide-product-design/

[开始使用 Axure RP ·Axure Docs](https://docs.axure.com/axure-rp/reference/getting-started-video/)

[人人都是产品经理 | 产品经理、产品爱好者学习交流平台 (woshipm.com)](http://www.woshipm.com/)



