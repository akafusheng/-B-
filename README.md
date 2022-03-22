# A-Comprehensive-Guide-To-Business-Product-Design 

# B端产品设计指南

## 名词解释





## 工具、资源推荐

原型绘制工具：[Axure](https://www.axure.com/download)

功能点图绘制工具：[XMind](https://www.xmind.cn/download/)

UML图表：[Visio](https://support.microsoft.com/en-us/office/install-visio-or-access-visio-for-the-web-f98f21e3-aa02-4827-9167-ddab5b025710)

在线的绘图软件：[Process On](https://www.processon.com/)

泳道图：[Creately](https://creately.com/zh/lp/swimlane-diagram-software/)

Java学习：[Java Tutorial (w3schools.com)](https://www.w3schools.com/java/)

SQL学习：[SQL Tutorial (w3schools.com)](https://www.w3schools.com/sql/)  

[SQL Teaching - The easiest tutorial to learn SQL](https://www.sqlteaching.com/)

[《编码--隐秘在计算机软硬件背后的语言》](https://awesome-programming-books.github.io/computer-system/%E7%BC%96%E7%A0%81%EF%BC%9A%E9%9A%90%E5%8C%BF%E5%9C%A8%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%BD%AF%E7%A1%AC%E4%BB%B6%E8%83%8C%E5%90%8E%E7%9A%84%E8%AF%AD%E8%A8%80.pdf)

[Ant Design - 一套企业级 UI 设计语言和 React 组件库](https://ant.design/index-cn)



## 技术路线

产品经理的工作内容可谓十分繁杂，需要掌握的知识体系也十 庞大：从业务分析到解决方案，从软件设计到项目实施，从数据分析 到运营管理。产品经理需要具备经营管理、企业运作、计算机科学、 软件工程、项目管理、数据分析、交互设计等各方面的知识。而这也正是产品经理工作的魅力所在——具备十足的挑战性，可以收获满满 的成就感。





### 界面设计流程

> 1. 产品经理绘制线框图原型，表达软件中每个页面的设计需求。
> 2. UE设计师协助产品经理完成交互体验，并制作交互原型。
> 3. UI设计师基于交互原型进行美工设计，生成切图文件。
> 4. 前端工程师拿到切图文件，进行前端开发，包括实现交互、动效等。



### 原型图绘制

产品经理需要将每个页面的排版样式、控件设计及交互效果，用通俗易懂的形式表达出来，以方便其他同事快速理解。线框图（也叫原型图）是一种很好的表现形式。绘制线框图的工具有很多，常见的有[Axure](https://www.axure.com/)、[Mockplus](https://www.mockplus.com/)、[墨刀](https://modao.cc/)、[Visio](https://support.microsoft.com/en-us/office/install-visio-or-access-visio-for-the-web-f98f21e3-aa02-4827-9167-ddab5b025710)等。

**线框图的重点在于说清楚界面上的交互功能设计，而非UI效果**。



使用 Axure 绘制原型图：[开始使用 Axure RP ·Axure Docs](https://docs.axure.com/axure-rp/reference/getting-started-video/)

原型图交互设计：[Ant UX | The Sitemap Template](https://ux.ant.design/)



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



##### RBAC权限模型

软件系统中典型的、完整的功能权限管理，除了**页面、功 能点、角色，还涉及用户组、资源等概念**。关于完整的功能权限设计，最 经典的理论是1995年由计算机科学家Ravi Sandhu提出的RBAC（Role Based Access Control）模型，描述了一套用户、角色、权限组的设计理 念，在业务系统设计中被广泛采用。如果产品经理需要设计功能权限管理 系统或模块，就必须理解RBAC权限管理模型。

RBAC模型可以简单地抽象为ER图，即每个用户都要被赋予一个或多个系统角色，每个系统角色都 对应一个明确的权限集合，包括对菜单、页面元素等资源的访问和操作权 限。RBAC模型中还引入了用户组的概念，即如果用户较多，可以对用户进 行分组，将角色和用户组进行关联。当有新用户时，只需要设置其所在的 用户组，就会将用户组关联的权限赋予新用户。如果用户角色需要批量调 整，只需要调整用户组和角色的关联关系，而不用重新变更每一个用户和 角色的对应关系。



##### 数据权限设计

角色在页面中能查到的**数据范围**，叫该角色的数据权限。所谓能查到 的数据范围，不是指能看到的数据字段，而是指能查出来的数据集合。例 如，针对订单列表页，数据范围可能是某个城市的所有订单，也有可能是 某个账户下的所有订单，也可能是某几个账户下的所有订单。

针对数据权限的控制，常见的实现方案如下：

- 方案一，**通过组织机构树控制**。该方案根据账号所在组织机构树中 的节点位置，来判断能够查询的数据范围。这种方式最复杂，但最灵活， 能够支持各种复杂的业务数据权限诉求。· 

- 方案二，**通过客户地区控制**。该方案根据账号所在区域来判断允许 查看的数据范围。这种方式简单、容易实现，但灵活性差，只能满足非常 初级的数据权限管理诉求



#### 文档的编写与管理

产 品 设 计 工 作 会 涉 及 一 些 文 档 ， 主 要 包 括 BRD （ Business Requirement Document ， 商 业 需 求 文 档 ） 、 PRD （ Product Requirement Document ， 产 品 需 求 文 档 ） 和 MRD （ Market Requirement Document，市场需求文档），三者的编写时间、受众、 编写目的和重点各不相同，见下表：

|          | BRD                                                          | PRD                      | MRD                                        |
| -------- | ------------------------------------------------------------ | ------------------------ | ------------------------------------------ |
| 编写时间 | 前期分析可行性时                                             | 开发之前                 | 立项之前                                   |
| 受众     | 老板、投资人                                                 | 研发人员                 | 市场、销售人员                             |
| 编写目的 | 论证商业模式的可行性                                         | 理解要开发的软件功能设计 | 说明产品要点                               |
| 编写重点 | 分析市场、产品定位、盈利模式，在业务系统的产品实践中，BRD很多时候是指业务部门提交的需求文档 | 功能描述、原型描述       | 概念性的产品形态介绍，描述产品的形态和大纲 |

在B端产品领域，BRD一般由需求方填写，用于提交需求；PRD由产 品经理编写；MRD在B端产品中鲜有涉及。

##### 商业需求文档（BRD）的管理

在产品设计工作中，无论是研发还是产品经理，都喜欢“好需求”，所 谓好需求，是指**具备业务价值的需求**。好需求都来自业务真实的痛点或问题，经过产品设计、开发实现后，能够帮助业务解决实际问题，带来收益和价值。

产品设计的好坏，首先取决于需求的质量。如果需求质量不高，产品 设计再用心，也难以产生价值。实际上，很多需求都只是需求提出者的灵 光一闪的想法，并没有经过严谨的思考。对于B端产品，尤其是业务系统， 业务方一般都有需求管理团队，负责调研、整理业务需求，提交给产品经 理。产品经理首先需要对需求进行判断，如果发现需求质量不高，就需要 和业务方反复讨论，判断需求的真实性。

**如果没有一些机制或手段，让需求提交者经过全面思考后再提交需 求，则可能会造成需求泛滥，需求质量低下，进而导致产品经理需要耗费 很多精力去鉴别这些需求的真实性和价值。**要求需求管理团队以正式BRD 的形式提交需求，可以在一定程度上提高需求的质量，并且可以作为正式 备档文件留存，帮助项目组提高协作效率。

[干货 | 送你一份非常实用的BRD文档模板！ | 人人都是产品经理 (woshipm.com)](http://www.woshipm.com/marketing/2196318.html)



##### 产品需求文档（PRD）的编写

在互联网公司，产品需求文档（PRD）由产品经理编写。不同公司、 团队、项目组对PRD的要求不同，有的比较严格，有的比较宽松，甚至在 有些创业团队中根本不需要PRD，在产品经理和研发人员的沟通讨论过程 中，功能就开发好了。但是，随着公司规模扩大，规范的PRD管理是非常 必要的，这可以让项目开展更加有序，大大方便产品经理和研发人员的沟 通，让知识传播与传承更加准确有效。

编写PRD是产品经理需要掌握的一项基本功，产品经理需要在PRD中 用清晰、通俗的文字将复杂、抽象的软件设计思路和方案描述清楚。

还要强调一点，产品经理不必急于写PRD，而要完成模型设计、流程 设计、界面设计、权限设计等工作后，再编写PRD。否则，如果方案还没 有理清就开始编写文档，会思绪混乱，不断返工。

[用Axure做一个产品需求文档（PRD）模板 | 人人都是产品经理 (woshipm.com)](http://www.woshipm.com/rp/3488031.html)



##### 文档管理要点

在传统的软件工程项目中，文档管理是一件非常严肃、严谨的事情， 文档的命名规范、审核流程、分发规范都有明确的要求。在互联网公司， 文档管理的要求相对宽松很多，但这并不代表文档管理可以随意而行。遵 循良好的文档管理规则，能够让工作井井有条，利于掌握项目进度，提升 效率；反之，如果不遵循这些规则，会造成工作混乱、失控、出错，甚至 影响整体项目推进。

文档命名要遵循一致的规范 一般来讲，我们常常按如下格式对文档进行命名： 

公司缩写+事业部+文档名称+版本号 

例如， M公司_分销业务_运营管理后台PRD_v1.0.docx 或者 M公司_分销业务_运营管理后台PRD_v20190513.docx 注意，对于同一个公司或事业部，名字中的“公司缩写”“事业部”要保 持一致；“文档名称”要反映这个文档本身是做什么的；版本号有专门的规范。

如果你要将某个修改后的文档发给别人，那么一定要给文档标记版 本。如果没有标识清楚，多次收到修订文件的同事会分不清哪个文档是最 新的，极有可能搞错版本，造成工作错误，引起很多不必要的麻烦。

文档的版本可以按照序列号的形式来标识。例如v1.0、v1.1，如果遇 到比较大的变化，还可以直接跳到v2.0或v3.0。这种方式有点类似软件的 版本管理，优点是可以看出版本的修订次数，或文档的“年龄”，例如一个 版本为v12.1的文档一定是一个很有历史的文档；缺点是无法一眼看出文档 的修订日期。按

文 档 的 版 本 也 可 以 按 照 修 订 日 期 来 标 识 ， 例 如 v20190503 、 v20190521。这种命名方式的好处是可以一眼看出文档的更改日期，缺点 是无法快速识别文档的修订次数。如果文档在同一天被修改分发了多次， 则还可以在日期后边追加序号，甚至时间，例如v20190503_01或者 v20190503_1623。按照修订日期来标识文档的示例如图6-48所示，看 起来同样很清爽。

值得一提的是，一旦选择了某个文档版本标识规则，就要统一按这个 规则命名，避免两套规则共存。

了在名字上体现文档的版本，在文档内部也要保留修订历史。文档 的所有变更，包括变更人、原因、时间、内容，都需要记录。采用文档版 本控制软件是一种常见的做法，类似CVS、SVN这样的版本管理软件能够 帮助你保存所有的文档版本。但是我们不能完全依赖外部工具，文档本身 也应该记录修订历史，这一点非常重要。



##### 将文档存档管理

文档是公司非常重要的知识资产，正式发布的文档务必上传到服务器 中存档，不能只保存在个人电脑中。即便公司或团队没有要求，产品经理 也要做好所有文档的线上备档、存储工作，以保证公司的知识资产安全。

在互联网公司，产品经理和研发工程师习惯将每一个版本的文档都上 传到Wiki系统中，实现文档的线上化存储，这是一种非常好的工作习惯。

文档管理要做好规范命名、版本管理、存档管理，虽然略显烦琐，但 却是必须重视、贯彻的工作。



#### UML和常用图表

在软件设计中，有很多抽象的概念、思想很难用文字表达清楚，通过 图形、图表来描述却很容易让人理解。诞生于20世纪90年代的统一建模 语言UML（Unified Modeling Language）就是一种常用的图形化语 言，经过多年发展，目前已经是一套成熟的规范和标准，是软件工程师做 抽象设计时的有力工具。 

UML规范中定义了类图（Class Diagram）、用例图（Use Case Diagram ） 、 对 象 图 （ Object Diagram ） 、 时 序 图 （ Sequence Diagram）、协作图（Communication Diagram）、状态机图（State Machine Diagram ） 、 活 动 图 （ Activity Diagram ） 、 组 件 图 （Component Diagram）、部署图（Deployment Diagram）等多种 图形方式，每一种图形都用来从某个视角解决某类程序设计的抽象描述问 题。

产品经理，尤其是B端产品经理，必须掌握UML的相关知识，能够通 过UML来表达阐述自己的设计思路，方便和开发人员进行高效的沟通。产 品经理常用的UML图包括ER图（UML中的类图）、跨部门流程图（使用 频率最高）、状态机图；可能用到的UML图包括活动图、用例图。接下 来，我们逐一进行介绍。

绘制文中提到的UML图表，常见的单机软件有Visio（Windows系统 中 ） 、 OmniGraffle （ macOS 系 统 中 ） ， 在 线 的 绘 图 软 件 推 荐 ProcessOn，这些软件上手都非常简单，读者可自行练习。



##### ER图

ER（Entity Relationship）图是一种描述实体对象（Entity）之间 关联关系（Relationship）的经典图表，由科学家Peter Chen于1976 年发明，最早被用于关系型数据库。

即使没有听说过ER模型，你在工作中肯定已经接触过它。例如，我们 在设计产品时，经常要讨论一些对象的对应关系，是一对多还是多对多， 这实际上就用到了ER模型。

ER图的呈现方式很多，比较常用的是UML的呈现 方式，实际上就是采用UML中的类图（Class Diagram）所规定的符号标 记规范来进行描述和呈现。

ER图的呈现方式很多，比较常用的是UML的呈现 方式，实际上就是采用UML中的类图（Class Diagram）所规定的符号标 记规范来进行描述和呈现。

##### 跨部门流程图

**跨部门流程图是一种相对复杂的流程图，可以清晰准确地描述分角 色、跨系统的业务流程**，跨部门流程图实际上是流程图的**泳道化**呈现，每 个职能部门在图中呈现出一条“泳道”的效果。严格来讲，流程图、跨部门 流程图不属于UML的范畴，尤其是流程图，拥有更加悠久的历史，在各行各业均普遍使用。

[流程图符号规则](https://www.edrawsoft.com/cn/flowchart-symbols.php)

开始、结束节点必须用专门的图形（多边形和椭圆形）来表达，这样容易让阅读者较为轻松地识别开始和结束的位置。 

每个流程只有一个开始节点，但可以有多个结束节点。 

尝试调整泳道的顺序，以便保证流程看起来清晰干净，而不是交 叉、缠绕在一起。



##### 状态机图

状态机图 （ State Machine Diagram ） 也叫有限状态机图 （Finite State Machine Diagram），是一种描述所有状态及状态之间流转规则的图形。

状态值必须是有限的集合，状态的所有枚举值（即状态值）必须能 够涵盖所有实际可能的情况。

状态值之间要互斥，不能出现二义性。 · 为了更准确细致地描述事物，状态还可以具备子状态，比如订单状 态“已取消”，可以定义对应的子状态“客户取消”“商家取消”“系统取消”。 

状态应该是能持续一定时长的，而不应该是很快就会结束的瞬时 态。例如，订单的状态可以是“待发货”“待评价”，但不能是“发货中”“评 价中”。 

通过研究状态之间所有可能的流转规则和逻辑，能够识别状态设计的合理性，并梳理清楚业务规则。如果用文字描述状态之间的轮转，会非常 不方便。通过状态机图，就可以非常好地解决这个问题。



##### 活动图（Activity Diagram）

活动图（Activity Diagram）是流程图的一种，用来描述一系列过 程。活动图和流程图最大的区别是，活动图可以描述并发工作的执行过 程，而标准流程图的节点必须是顺序执行的，只有判断节点才能引出两条 分支。



##### 用例图

用例图（Use Case Diagram）从用户视角来描述系统的操作功 能。简单来讲就是**某个角色或用户在不同场景下能做什么。**

以上介绍了产品经理常用的图表，产品经理绘制图形的主要目的是说 明清楚设计思路，这些图表可能给技术人员看，也可能给业务人员看。在 实际工作中，产品经理应该尽量使用简单的方式，让别人理解自己的设计 和意图。不建议使用过于复杂的UML规范，因为不是所有人都具备UML知 识，如果采用了复杂的UML标记体系来绘制图形，会导致其他人看不懂， 失去沟通的意义。

多 看 UML 实 例 可 以 快 速 准 确 地 理 解 各 类 图 表 。 推 荐 学 习 网 站：[Welcome To UML Web Site!](https://www.uml.org/)该网站对UML进行了详细讲解，并且提供了丰 富的案例，是非常好的学习资源。



### B端产品经理与技术方案

产品经理要懂技术，这样可以设计出更好的产品方案，尤其是B 端产品经理，更需要理解技术体系架构，因为B端产品的结构设计不 仅和业务有关，还和技术架构有关。

#### 产品经理是否要懂技术

B端产品经理**需要**具备基本技术常识、软件开发常识，这样可以 让设计的方案更加合理、可落地。和C端产品相比，B端产品更重视业 务逻辑的抽象过程，产品设计方案和技术方案的相关性更强，甚至有 时候产品设计方案本身就是技术方案，例如SDK产品、基础服务产 品、消息中间件产品等的设计方案。

懂技术的产品经理在设计产品方案时，能够在一定程度上预估技 术实现的可行性和实现成本，或至少能具备基本的认知，知道什么时 候、什么情况下需要和技术人员提前沟通讨论，从而保证产品设计合 理可行，既能提升合作效率，也能赢得技术人员的尊重和信任。

在互联网圈流行一句话：“产品经理懂技术，谁都挡不住”，虽然 是一句玩笑，但体现了大家对产品经理懂技术这件事的看法。无论是 研发人员、运营人员还是交互设计师，都认同产品经理懂一些技术知 识会对产品设计有帮助，对项目协作有益处。

优点：

- 避免产品过度设计
- **避免技术过度设计**
- 与技术人员沟通顺畅
- 预判需求的可行性
- 评估工时合理性



#### B端产品经理的技术知识要求

##### 具备基本的技术知识体系

###### 理解一门编程语言

编程，对于没有接触过的人来讲，是一件神秘且高深的事情：满屏幕 的代码像天书，肯定需要投入巨大的时间和精力来学习。 实际上，写出有工程实践意义的代码确实很有挑战，但是理解编程的 逻辑并不难，只要静下心学习，无论是文科背景还是理科背景，都可以学 懂，而且会发现程序设计是一件很有趣的事情。 B端产品经理可以通过学习一门编程语言，来理解程序设计的基本逻 辑，例如什么是函数、返回值、循环、编译、发布等。学习的重点不是编 写出能执行的程序，而是理解程序设计的基本原理。

程序语言的种类繁多，但本质相同，从C++或Java这些主力编程语言 入手学习就是不错的选择。学习了解一门主力开发语言后，如果有兴趣和 精力，可以学习一些轻量级的、在工作中可能会用到的编程语言。例如， 学习使用Python爬取网页内容进行数据分析；学习使用Excel VBA进行复 杂数据处理。



###### 掌握并使用SQL

SQL（Structured Query Language）是经典的关系型数据库处理 语言。在业务系统领域，关系型数据库不论是在过去的几十年，还是在未 来的若干年，必然是长期存在的主流数据存储方案。

产品经理掌握SQL在实际工作中是非常有用的。例如，在做数据分析 时，常常需要从数据库导出数据来分析，如果不会写SQL语句，就需要每 次都求助开发人员，效率太低；其次对于复杂的数据处理逻辑，如果不会 用SQL语句进行预处理，后续的数据处理将变得非常麻烦。 学习使用SQL，首先需要理解数据库及表结构，这对于抽象建模思维 的培养非常有帮助。



###### 了解网络通信等计算机常识

B端产品经理需要广泛学习计算机相关的基础知识，例如网络与通信 原理、操作系统原理、微机原理等，至少要理解TCP/IP协议、UDP协议分 别是什么，二进制、十六进制的运算法则，字节和字的长度概念，对称密 钥密码体系和非对称密钥密码体系的区别，等等。

如果对这些概念没有基本认知，那么将很难理解为什么HTTPS比 HTTP安全，为什么有时候需要通过二进制来控制标记位。这些常识都是 软件设计随时会用到的基本知识，不仅在技术方案设计中会涉及，在产品 方案设计时也会涉及。

计算机技术涉及的知识面非常宽泛，从编程语言到数据库设计，从通 信协议到算法策略。对于产品经理来讲，技术知识的积累是一个厚积薄发 的过程，不可能通过短时间的突击学习就掌握所有知识点，只能在实际工 作中遇到新的词汇或概念时，认真查阅资料、理解揣摩，在长期积累中融 会贯通。



##### 了解程序设计的MVC范式

编程语言种类繁多，无论采用哪种语言进行程序设计，都要遵循经典 的软件工程设计模式——MVC模式。

 MVC是**Modeling、View、Controller**的缩写，代表软件设计的分层 理念。Modeling指数据模型，View指前端交互视图，Controller指业务 逻辑，MVC模式下的软件分层结构如图所示。任何一套软件系统运作 的本质都是相同的：用户在前端交互层操作后，系统通过业务逻辑层处理 数据层的数据。不论是BS架构的系统（例如通过浏览器访问的管理后 台），还是CS架构的系统（例如App应用），都会遵循MVC模式搭建程序 结构。将一套软件系统分为**数据、业务逻辑处理、前端交互**三层来设计、 开发，可以非常有效地保证程序结构合理、逻辑清晰。

[MVC - 术语表 | MDN (mozilla.org)](https://developer.mozilla.org/zh-CN/docs/Glossary/MVC)



###### 熟悉接口与调用模式

在软件开发中，接口是一个非常重要的概念。所谓接口，是指**两个对象进行通信的方式和协议**。软件领域的接口和我们生活中所使用的硬件设 备的接口（例如USB接口、苹果的Lighting接口、3.5mm耳机接口等） 类似，每种接口都有约定的格式和规范，只要在设计时遵循了约定和规 范，就能够方便地进行信息交换。

在软件设计领域，小到一个软件模块，大到一个软件系统，都会有若 干接口，实现不同模块、不同系统之间的通信。一般来讲，每个接口都应 该实现一个具体的功能，接口需要有明确的输入，以及明确的输出（有的 时候输出结果为空）。例如，调用客户姓名查询接口时，需要传入客户 ID，执行后返回客户姓名。

在跨团队、跨模块的软件开发中，接口的设计规则需要在设计技术方 案时就协商好，然后各方团队各自开发，在约定的时间一起联调，进行集 成测试。

接口之间的调用模式分为同步调用模式和异步调用模式两种，产品经 理需要理解这两种模式的区别，因为这不仅是技术问题，也会影响产品方案。

[同步调用和异步调用](http://www.woshipm.com/pd/3085570.html)



###### 理解软件工程的“搭积木”设计

软件工程是一项既复杂又简单的系统性工程。说它复杂，是因为一整 套良好运转的体系是由数百万行代码构建而成的；说它简单，是因为本质 上软件体系是无数组件化的小模块拼装而成的，每个研发人员或研发团队 只需要维护自己负责的组件与代码模块，复杂度会降低很多。

软件的设计应该像搭积木那样，通过自由拼接组装来实现复杂的功能 模块，这样既能保证系统的灵活性，又能避免重复开发，降低成本。**如果不能将软件分解成像积木那样的小模块，而是焊死的一块铁板，那么系统将彻底丧失灵活性。**

在技术体系中，有两个非常重要的概念在支撑着接口化、服务化的设计理念的落地，即SOA（Service Oriented Architecture，面向服 务的架构体系）和微服务。SOA和微服务从本质上讲区别不大，只是微服 务鼓励去中心化.在传统企业 的SOA落地方案中，这是很重要的ESB（Enterprise Service Bus） 模块（服务的中心化调度模块），而按照微服务理念设计的方案中则不会 有这一层。

企业的各 个软件或产品并不是独立的、割裂的，而是深度结合、互相支撑的。架构 的理念在高阶的B端产品设计中非常重要，同时B端产品的设计体系和技术 架构也有着一脉相承的设计思路。理解技术架构对设计产品架构大有裨益。



###### 掌握数据库与SQL

在业务系统设计中，建模工作是最重要的，模型的好坏将从本质上影 响系统的灵活性和可扩展性；而设计数据库表结构正是对模型设计的一种 落地实现。如果你能够理解模型、ER图，再进一步理解数据库表结构，那 么你对业务系统的技术实现会有更加深刻的理解和认识，这对产品设计工 作会有很大帮助。

我们所说的数据库主要是指关系型数据库（RDBMS，Relational Database Management System），这是在20世纪70年代提出的一种 计算机数据处理方案，经过几十年的发展，关系型数据库已成为目前业界 最经典和流行的数据处理方案。SQL是对关系型数据库进行数据增删改查 操作的计算机语言。 常见的关系型数据库包括IBM的DB2、微软的SQL Server、甲骨文的 Oracle，以及被甲骨文收购并开源的MySQL，每一种关系型数据库产品 都有自己的SQL规范，但核心的语法规范是相同的。

www.sqlteaching.com：该网站是目前我接触过的最好的SQL学 习资源。网站通过一个个案例讲解了SQL中的每个概念和语法，并且提供 了非常强大的在线练习功能，这对学习SQL至关重要。虽然是英文网站， 但是讲解深入浅出，很容易理解。



### 让产品落地并不断生长

产品方案、技术方案设计完成后，只相当于万里长征走完了第一 步。接下来进入产品研发环节，以及产品上线后的运营推广和迭代优化环节。

在产品开发及运营推广工作中，B端产品经理要从整体上管理进 度、控制风险。产品经理会面临各种复杂的挑战，既需要有很强的专 业能力，又需要有灵活变通的处事能力。产品经理很像一个大管家，不仅要负责产品功能设计，还要统筹协调各种资源，确保一系列工作 都能同步开展，最终拿到希望的结果，产生业务价值。



#### B端产品的项目管理与实施工作

需要说明的是，在很多创业公司，甚至是具备一定规模的公司和 团队中，并没有项目管理团队及专职的项目经理，需要由公司的产品 负责人来制订项目管理制度初稿，并负责项目管理。因此，产品经理 有必要全面理解并掌握项目管理工作的目标和内容。

##### 为什么需要项目管理

当公司或团队规模较小时，工作随意而快捷：客户早上提了需 求，产品经理在黑板上写写画画，不必写正规的PRD，直接和研发人 员沟通就行；不必做回归测试，产品经理简单试试功能，晚上请研发 工程师操作，产品就能上线了；不需要运维部署，速度快，效率高。 这种现象在初创团队和创业公司中很常见，业务开展初期，问题多， 想法多，市场变化快，没有条条框框的约束，拼的就是速度！ 

随着公司规模变大，团队人数增多，作坊式工作方法不再适用： 缺少流程制度，会让多人协作变得混乱失控；没有统一优先级裁定， 会让跨部门项目引发争执；没有需求管理规范，会让业务部门抱怨产 品研发部门配合不力，产品研发部门抱怨业务部门不靠谱，团队关系 剑拔弩张。这种情况下，如何才能保证产品研发团队高效运转？如何 保证软件产品能够按计划交付？如何让用户满意？要解决这些问题， 就必须从作坊式的生产模式转变为标准化、专业化的生产模式。 

优秀的项目管理是互联网公司在复杂环境下保证软件开发按计划 推进、落地的关键，也是保障规模团队的产品研发效率和质量的核心要素。



##### 互联网项目管理的工作重点

- 设计并优化项目管理制度

- 负责大中型项目的立项实施

  

##### 如何协调并推动跨端协作

- 明确项目收益价值
- 找到KP并积极游说，产品经理要找到KP（Key Person，关键人 物），并积极游说，获得支持。
- 保持强的推动力与执行力，通俗点儿说，强执行力和推动力就是指能够记着事儿，不忘事 儿，上着发条追进度，盯过程，要结果。



##### 如何把控项目进度

B端项目面临的第二个挑战是项目的周期长，复杂度高，变数大，项目 进度不好把控。如果做到以下几点，就能够较好地控制项目进度。

- 细化工作，明确交付
- 通过机制把控进度
- 编写内容清晰的项目日报或周报，项目经理要利用项目日报或周报来争取关注度和资源，解决项目中遇 到的问题。本周进展、风险、计划、整体进度
- 保持足够的责任心



#### B端产品的运营管理

B端产品上线后，需要开展运营推广工作，除了产品经理，运营 推广还会涉及产品运营人员和业务运营人员。而且，B端产品经理、 产品运营人员、业务运营人员三者的工作职责往往有很多交叉和重 叠，这就可能导致冲突，影响工作效率。产品经理需要深刻理解三者 的工作目标、工作方式，处理好协作关系，这样才能保证工作顺利开 展。



##### B端产品运营岗的工作内容

B端的产品运营岗位在行业内没有公认的定位或定义，但是既然 是产品运营，肯定要围绕产品展开，而不是仅仅做纯粹的业务管理工 作。

对于支持内部业务的B端产品运营岗，工作目标是通过挖掘B端产 品的能力（即对现有功能进行推广、协助完成产品的升级优化），帮 助企业解决业务问题。其中，业务问题可能是营收增长问题，也可能 是风险控制问题。 

B端产品运营岗位的工作内容主要包括产品功能推广培训、问题解答处理、需求采集过滤、项目效果分析、业务诊断分析几个方面， 我们来分别介绍。



###### 产品功能推广培训

B端产品的功能上线后，一方面要在线上进行推广宣传，例如消 息推送、公告通知等；另一方面，针对比较复杂的升级改造，还需要 组织业务团队进行现场培训。 产品经理也要对B端产品的推广负责，但很多时候产品经理需要 运营人员的协助和支持。比如，产品宣传时可以做一些吸引人的易拉 宝，摆在业务团队里进行曝光；也可以组织一些功能使用熟练度的考 核比赛，对于应用熟练的一线人员进行奖励。这些工作都需要由专门 的产品运营人员跟进。



###### 问题解答处理

业务用户在使用系统的过程中，肯定会遇到各种各样的问题和困 惑，有时候是遇到了Bug，有时候是因为不理解规则，有时候是不知 如何操作，产品运营人员需要在线上对问题进行答疑处理，帮助用户 解决问题。



###### 需求采集过滤

产品运营人员和一线业务人员接触多，有更多的机会了解一线人 员的工作状况、感受，并收集一线业务人员的直接诉求。优秀的产品 运营人员能够识别并挖掘好需求（真正会产生影响的需求），和产品 经理一起持续优化产品。反过来，产品经理收集需求的途径很多，其 中很重要的一个途径正是通过产品运营人员收集并提交需求。



###### 项目效果分析

一般情况下，产品经理要对上线的功能进行持续的数据分析和观 察，这个工作也可以委托产品运营人员完成。有的时候，公司会直接 安排产品运营人员作为中立方，独立考核项目效果和收益，给出客观 分析。



###### 业务诊断分析

高阶的产品运营人员还要和产品经理、业务团队一起诊断业务， 分析问题，提出解决方案，并推动解决方案落地执行。



##### 产品经理、产品运营人员、业务运 营人员如何高效协作

随着互联网公司业务模式越来越重，产品经理和产品运营人员、 业务运营人员的合作关系问题、权责分配问题越来越突出。如何体系 化地解决三者的合作问题，推进协同共赢？如何让产品经理专心聚焦 于创新和业务本身？ 影响合作关系的因素很多，主要包括人际因素、产研文化、组织 架构。其中人际因素因人而异，产研文化取决于公司创始团队的背 景，这两者很难通过一些动作或方案来改善。此处，我们重点谈一下 组织架构问题，这是解决合作关系问题最有效、可操作性最强的办 法。同时，在探讨组织架构的过程中，大家也可以更加深刻地理解三 者之间配合问题的成因和本质。

###### 调整组织架构改善合作关系

互联网公 司取得成功的诀窍之一就是，频繁地调整组织结构，尝试各种安排， 在各种调整中很可能实现破局，或者产生“鲶鱼效应”。



##### B端产品的迭代优化

###### B端产品的需求管理

产品投产后，还需要不断收集、挖掘新的需求，进行持续的升级迭 代，以完善系统功能或优化业务流程。如何持续获取有价值的需求？如何 对需求排优先级并实现之？此时，需求的收集和管理工作就显得非常重 要。

需求的收集和管理是产品经理的一项基本工作内容。不要轻视看似烦 琐的需求管理工作，对业务和产品的理解正是在这些工作中逐渐形成的； 而确认需求的优先级、确认迭代工作的计划安排，更能培养对业务的准确 判断力。

**收集需求**

B端产品的需求来源十分广泛，包括一线用户、产品运营人员、业务运营人员、业务领导等的反馈，需求内容也非常丰富，包括交互体验优化、业务调整要求、业务管理要求等，而能采集需求的手段也丰富多样， 包括一对一面谈、问卷调研、轮岗实习，等等。

需求收集的要点之一是，通过各种渠道全面、迅速地收集建议，而 且，无论是否采纳，都要给出反馈，例如意见**是否采纳**、**预期的解决时间**等，这样才能形成持续的良性互动。

收集到需求后，产品经理不应该简单被动地接受、执行，而要识别需 求背后的真实问题、判断需求的价值，这很考验产品经理的判断能力。在 日常工作中，产品经理要勤于思考，尽可能地理解业务，以提升自己的判 断能力。面对需求时，产品经理可以思考以下问题，帮助自己准确、迅速 地判断需求的价值：

- 这个需求背后的真正问题是什么？
- 这个问题是否有简单快速的解法？
- 这个问题的影响面有多大？如果只是个案，是否值得投入精力去研 究解决？
- 如果是共性问题，优先级和紧急程度如何？



**需求管理池**

对于收集到的需求，经过初步判断、过滤后，要放入需求池进行管理跟进。可 以通过一套项目管理软件（例如[JIRA](https://www.atlassian.com/zh/software/jira/guides)、[Teambition](https://www.teambition.com/)）对需求进行管理，按 照公司统一的项目管理规范来实现。



###### 迭代管理

收集需求后，产品经理要根据优先级进行需求跟进和方案设计；方案设计完成后，便进入开发、迭代环节。

软件的代码需要不断地优化。如果软件升级迭代过程中只做产品功能 需求，而不做技术优化，随着功能的积累，软件系统会变得越来越脆弱， 运行速度会越来越慢，甚至频繁宕机。因此，在日常的迭代升级中，必须 给技术优化预留足够的资源。 

应该投入多少资源做技术优化？这个问题在产品经理和研发负责人之 间似乎很难达成一致。研发负责人想多投入一些资源优化系统，而产品经 理则认为应该首先解决业务需求。如何平衡业务需求和技术优化之间的资 源分配问题呢？ 

从大的方面来说，这和系统所处的阶段有很大关系，不同阶段资源分 配的思路完全不同。结合业务发展周期，我们将系统建设归纳为四个阶 段，分别是初创阶段、瓶颈阶段、重构阶段、稳定阶段。



**初创阶段** 

在初创阶段，业务还处于探索试错期，业务本身不一定能成功。在这个阶段，系统从无到有地构建起来，研发团队要开足马力支持业务，本阶段的重点在于“活下去”。构建的系统是一套全新的干净系统，没有任何历史包袱，因此，可以铆足劲儿开发业务功能，而不用太在意代码、架构的 合理性，此时可以只预留10%的资源做技术优化，甚至不做技术优化。只要研发团队的水平靠得住，一套全新的系统在全力运转的状态下对业务支 持一年的时间，应该是绰绰有余的，而一年正好是验证业务是否能够存活 下去的关键时间点。 

**瓶颈阶段** 

经过一年的探索，证明了方向是正确的，业务取得了初步成果，并继续保持高速发展。业务对新功能的渴望持续且强劲，产品研发团队依然开 足马力，但此时系统已经显现出疲态，“**技术债**”问题出现：曾经的设计缺 陷、硬编码、架构不合理等问题逐渐凸显出来，系统三天两头出问题， Bug繁出，稳定性差，与此同时，业务需求继续井喷！ 对于产品研发来说，一半的资源被修复Bug和迫在眉睫的技术优化占 用，另一半资源被难以维护的老代码拖住。产品研发团队既不能痛快地满足业务需求，也不能爽快地一次性解决系统结构问题。此阶段可能会持续1 年到1.5年的时间，可谓整个产品研发团队的“噩梦时期”。 、

**重构阶段** 

业务继续发展且相对稳定，业务需求依然络绎不绝，但系统已濒临崩 溃的边缘。所有人都明白，偿还技术债的终极时刻来临了：公司层面决定，业务需求给技术重构让路，留给研发团队充足的时间重构系统，一次性解决历史问题。此阶段可能会安排80%的资源做技术优化重构工作，包括代码解耦、拆库拆表、中间件升级、接口化、服务化等。 对于瓶颈阶段和重构阶段分别持续多久、在什么时候发生，这个问题 很难准确回答，取决于业务情况、系统状况、技术团队的话语权等因素。 此外，也有“边开飞机边换引擎”的成功案例，即在不影响业务的情况 下，持续升级系统，开发新功能的同时完成系统重构，但难度相对较大。 需要结合具体的系统架构和实际情况来判断采取什么方案。

 **稳定阶段** 

该阶段业务发展稳定，系统运行平稳，Bug少，不宕机。业务需求依 然不停地提出，但此时研发工作显得井井有条。即便如此，依然需要预留 10%到20%的研发资源持续做技术优化，这是保证系统持续稳定的秘诀。



#### B端产品的数据分析

通过数据支持决策，是互联网企业在激烈的市场竞争中快速试 错、纠正方向、取得成功的不二法门，互联网人必须具备以数据驱动 业务决策的意识和习惯。对于产品经理来说，无论是业务问题诊断， 还是项目效果分析，都需要通过数据分析来进行论证和判断，因而数 据分析能力是产品经理的必备技能之一。



##### 数据分析流程

B端产品从决策、设计到落地、运营，整个流程都需要全面的数据支持 和数据驱动。各个环节要分析的数据不同，得到的结论也不同，但是数据 分析的思路和本质是相同的，B端产品经理要理解并掌握数据分析工作的特 点和要点。

明确主题--提出假设--验证假设--产生结论

实际上，一套BI软件产品的重要功能之一，就是实现类似Excel数据透 视表的功能，可以让分析人员从各个维度探查数据。而数据仓库（Data Warehouse）要做的事情，就是对各种明细数据提前按照各种维度加工计算好，等待BI的多维度探查和展示。



##### 数据分析的要点

做好数据分析工作需要三个核心要素，分别是**方法工具**、**业务知 识**、**细心耐心**，三者缺一不可。

###### 方法工具

作为互联网产品人，至少应该掌握并熟练使用以下数据分析相关 的方法或工具。

- 统计学：掌握**基本统计学常识**，帮助自己判断、认识数据特 点。例如，要理解方差、均值、中位数、众数等概念。
- Excel：Excel具备各种强大功能，足以作为初级、中级数据分析工作者的首选甚至唯一工具。
- SQL：掌握SQL可以快速提取原始数据，并完成数据预处理。
- 数据可视化：在工作实践中，多数情况下都是通过观察图表来 发现、识别问题的，采用合适的图表形式，可以让分析更直观、高效，例如通过瀑布图、直方图、桑基图等观察数据特征和变化情况。
- 计算机数据基础：有的时候我们需要对原始数据进行一些编码 处理，这就需要理解一些编码基础知识，例如什么是ASCII、UTF-8、 UTF-16、Unicode，如何通过UltraEdit等软件进行编码处理（例 如，有时在Linux环境下运行SQL语句，导出的数据需要进行编码转 换才能在Windows环境下使用，如果自己不会处理，就需要每次都求 助于人）；此外还要了解计算机常见的数据存储格式，例如CSV、 JSON、XML等。
- 正则表达式（Regular Expression）：正则表达式是一种非 常巧妙的、用来处理文本的逻辑公式，在某些时刻，使用正则表达式 可以解燃眉之急。
- 数据分析方法论：基于不同的分析诉求，有很多成熟且经典的 数据分析方法论，例如分析C端产品的获客增长模型AARRR、分析客 户消费行为特征的RFM模型、分析留存率的COHORT模型，这些方法 论中蕴含了成熟的分析思路和手段，是针对各种确定的分析场景的最 佳实践。

更高阶的数据分析技能和知识还包括Python、 SPSS、ETL、数据仓库等，适合专业的数据分析师学习。

###### 业务知识

业务知识既包括行业知识、领域知识，也包括具体公司的商业模 式、运营流程细节等。业务知识是数据分析的灵魂，是指引数据分析 过程朝着正确方向前进的明灯。如果不具备业务知识，即使对各种方 法论和工具都很熟悉，分析工作也会无从下手。

因此，产品经理还需要补充各种业务知识，例如销售知识、供应 链知识、仓储知识等，需要产品经理根据所处行业选择并学习。

###### 细心耐心

数据分析的过程可能是有趣的、富有挑战和成就感的，因为你需 要充分调动脑细胞，进行各种思维激荡，发现真相后会欣喜异常；也 可能是无趣的、徒劳的甚至令人沮丧的，因为你可能耗费了心血、精 力、时间，最后没有得到有价值的结论，感觉一无所获。因此，做数 据分析需要有足够的细心和耐心，能够在遇到挑战、困难、阻碍时不 气馁，坚持下去，这样才能取得成果。



##### 数据分析报告

经过反复分析、验证，真正的原因或结论终于浮出水面，我们需要制 作数据分析报告，把这一成果呈现给领导或同事，此时，**如果因为报告太粗糙而掩盖了数据分析的价值，岂不十分遗憾！**因此，学习如何制作优秀 的数据分析报告是很有必要的。

一份逻辑清晰、简明扼要的报告，可以让阅读者轻松、准确地理解并 掌握报告内容。一份格式编排严谨、注重细节的报告，可以体现制作人的 严谨态度和专业素养。

###### 报告编写思路

数据分析报告的常见结构和逻辑论证的结构相似，一般按照“总分 总”的形式编写，包括提出论点、进行论证、陈述总结三部分。

**提出论点**：报告的开篇要简明介绍背景，以及分析的结论，让人产 生兴趣并继续关注下去。如果一开始就介绍分析的细节，估计阅读的人或 听众都会摸不着头脑，一会儿就昏昏欲睡。 

**进行论证**：论证过程要有**数据支撑**，并且数据的呈现一定要专业又 易读。人们都喜欢看简明易懂的数据图表，而不喜欢读复杂的数学推演。 因此，配有丰富、清晰图表的报告读起来会给人生动有趣感，讲解起来也 容易吸引人的注意。 

**陈述总结**：再次阐述并强调结论，加深阅读者或听众的印象。 无论是向上级汇报工作，还是给同事分享材料，按照上述结构编写数 据分析报告都是比较有效的方法。



###### 报告的排版美化

在实际编写报告时，无论是用PPT还是 用Word，都需要十分注意这些问题。

没有数据来源：这就像食品包装上没有产地和成分，会导致阅读者 无法判断结论的可信性。标明数据来源可以体现数据的合理性、合规性、 合法性。 

没有标记坐标轴含义：图中没有标记坐标轴含义，阅读者需要猜测 横纵轴数据的含义。 

没有标记单位：两张图表的纵坐标呈现的是收入，但是却没有标明 单位（如“元”或“万元”等），阅读者难以理解收入到底是多少。

 数字格式不规范：对于纵坐标的收入数据，两幅图都没有采用千分 符；小数部分的格式也不规范，左图不含小数位，右图却包含2位小数，但 都是0，没有意义。

漂亮的图表可以让报告看起来专业且赏心悦目，遗憾的是，Excel默认 生成的图表在美观方面总是略有欠缺。这里推荐国内Excel图表制作专家刘万祥的著作《Excel图表之道》，书中详细且清晰地讲解了如何制作商务范 儿的专业图表。通过学习和练习，相信你绘制的图表会更加美观和专业， 成为令人眼前一亮的加分项。



### 支撑企业运转的整套产品体系

如果你想对自己从事的产品领域有更加深刻的认识，想获 得更广阔的职业发展空间，就必须学习、掌握企业级应用架构的搭建。

所谓**企业级应用架构**，是指企业的所有软件系统设计、集成的方式。这些系统被按照合理的结构组装起来，支持企业经营管理的方方面面。“企业级应用架构”中的“应用”就是指**软件系统**。



#### 什么是企业级应用架构

**企业级应用架构正是指企业的各个软件系统有机集成在一起的方式**。

通过OA系统解决内部员工管理与协作问题；通过HRM系统解决 HR业务管理问题；通过OCRM系统解决客户开发管理问题；通过 SRM系统解决供应商管理问题，等等。

企业信息化建设已经发展了几十年，仔细思考你会发现，传统企 业和成熟互联网企业的应用架构并没有本质的区别，无论是传统企 业，还是互联网公司，发展到一定阶段后，都需要一整套体系化的应 用架构来支撑其运转。良好的、合理的应用架构可以支持企业高效开 展业务，控制经营风险；而混乱的、不合理的应用架构则会限制企业 的快速发展，成为企业发展与变革的瓶颈.

#### 学习企业级应用架构的益处

##### 加深对业务和产品设计的理解

学习企业级应用架构，最直接的好处是让你对业务的理解变得**全面且深刻**。

在学习企业级应用架构的过程中，产品经理必然要理解企业的组 织架构、职能部门的设计；理解企业在不同阶段、不同的业务情况 下，部门之间的权责分工、组织架构的演进等，从而对企业是如何运 作的形成清晰的理解。 理解支撑企业运作的成熟产品方案。

学习企业级应用架构还能帮助理解企业级架构设计的背景和原 因，理解应用架构的设计是随着业务发展的，**是循序渐进地演变的， 不是一蹴而就的**。

掌握企业级应用架构的全貌，能够拓宽自己的视野，思考问题时 能够跳出自己负责的业务和产品的范围，尝试从企业、行业、产业的视角考虑，尤其是从企业整体经营发展的角度去思考、设计方案，能 有效地锻炼并**培养自己的大局观**。

学习企业级应用架构的搭建，既可以为专业方向的发展打好根基，支撑你走得更远；也可以为管理方向的发展做好知识储备，练就作为管理人员需要具备的**全局观**。

ERP（Enterprise Resource Planning，企业资源计划）传统的ERP软件相当于集合了典型电商公司的后台模块、财务系 统、仓储系统、配送系统、采购系统。比较典型的**ERP软件产品厂**商 有SAP、Oracle、用友、金蝶。



#### 通用的企业级应用架构设计

##### 业务定位和边界要清晰

一套应用系统是为了解决某一类业务问题而存在的，对应某一个 业务模块。如果业务部门本身权责定义混乱，必然会导致对应的应用 系统定位混乱，进而导致后续的维护、升级、管理困难。因此，在设 计业务系统之前的业务调研非常重要，如果发现不合 理的地方，需要和业务方一起确认、梳理清楚，再开始设计。

##### 系统要实现松耦合、高内聚

业务的需求是在不断变化的，这要求应用系统是灵活、可扩展 的。一个扩展性强的应用系统，对外界来说，应该是简单、易理解 的，与外部系统的接口应该简明、可拆解；在系统内部，各个模块应 该是高度聚合的，模块之间要实现松耦合，什么意思呢？可以借助汽 车来理解：系统的各个模块就像汽车的轮子、发动机等组件，应该功 能明确、独立、灵活（高内聚），而且各个组件通过轻松组合（松耦 合）就能得到一辆完整的汽车（相当于完整的系统）。

##### 不要让易变的新业务影响现有业务的稳定性

新业务发生变化的可能性大，失败的可能性也大，因此可以考虑 新建独立的微小型应用系统来支持新业务，以避免改造成熟核心系 统，影响其稳定性和健壮性。

##### 系统之间要实现数据的单向流转

系统之间应尽量保证数据单向流转，确保数据流可回溯，这样才 能保证数据的一致性和可追溯性。混乱的数据流转会造成应用架构管 理和企业经营管理的灾难。

##### 综合考虑架构的合理性和业务发展的需要

应用架构设计的首要目标是支持业务发展。在企业创业初期和成 长时期，业务还在试错，活下去是关键，系统建设要全力支持业务， 而不要过于追求架构的完美，这一点我们已经强调多次。如果一上来 就谈论整体架构的合理性，很可能花费巨大成本实现了合理架构后， 业务已经取消或失败。

**优秀的架构师和CTO要懂得在合理架构设计和灵活多变的业务需求之间做出权衡。**一方面要保证整体应用的大框架是合理的，因为如 果大框架有偏差，修正的代价会非常高；另一方面，在必要时要允许 局部偏差的存在，局部偏差的修正成本是比较低的。**对于某条产品线 的负责人和产品经理来说，也要在架构的合理性和整体的业务需求之 间做出权衡。**

##### 深入思考新系统与旧系统的关系





## 参考文献

[决胜B端 (豆瓣) (douban.com)](https://book.douban.com/subject/33454250/)

产品设计方法 https://www.smashingmagazine.com/2018/01/comprehensive-guide-product-design/

[开始使用 Axure RP ·Axure Docs](https://docs.axure.com/axure-rp/reference/getting-started-video/)

[人人都是产品经理 | 产品经理、产品爱好者学习交流平台 (woshipm.com)](http://www.woshipm.com/)



