---
title: 软件
author: 杨翼臣
date created: 星期三, 4月19日 2023, 2:35:28 下午
date modified: 星期三, 4月19日 2023, 4:03:24 下午
tags: [软件工程 ppt]
aliases: 
---
# 软件
## 什么是软件？
软件不仅仅是程序代码，还是相关库和文档的集合。

## 什么是软件产品？
为了用户提供的需求或者其他特定的需求而开发的东西可以拿去卖的就是产品。

## 工程
一般的工程就是说用定义明确的已有的科学原理和方法来开发一个项目或产品；

## 软件工程
就是利用了工程的思想，使用定义比较明确的科学原理、方法、和程序去开发软件处产品；

要达到的成果是开发出一个高效可靠的产品软件。

## 为什么需要将软件看成一项工程？
- 大型软件：程序规模大的话，就要有科学的过程和思路。否则建造过程会很混乱。
- 可扩展性：用系统且较科学的方法建造软件方便后期进行拓展、因为把项目分成了很多小块儿，我能明确知道是工程的哪一块需要改进和增强。
- 成本：将软件看成一项工程，用工程的思想去提前规划好预算、能够方便有效的控制和计算整个项目的成本。
- 动态性质：工程是会变动的，软件在开发过程也是会变动的。
- 质量管理：条理清晰、分工明确的、路线明确的开发过程也能更加方便的问责、监督、和完善。


## 软件的三种类别
### 静态类s
在写代码之前就能完全理解功能和需求。或者说就只实现既定的功能即可。如计算器、扫二维码的app、弹窗广告软件这些等等。写完就不需要更改了。用户的需求也基本不变了。总不能说扫二维码的app还能再添加什么将非二维码转变为二维码后识别吧。一般需求就不会变了。

### 实用性p
将不同的程序集合在一块儿的软件。一般定义程序能做什么。比如游戏。就是将各种程序集合在一起。比如登录程序、客户端登录程序、游戏本地程序、游戏论坛程序。等等。
### 嵌入型e
简单理解就就是需要不断更新和维护的软件，需要根据现实世界的变化不断地演化。比如在线货币交易所软件、疫情期间的健康码小程序等等。这些软件和小程序需要根据现实的政策或者需求不断的变化功能和实现功能。就是一种嵌入型的软件。



# 开发的过程需要明确的几个概念
## 软件进化（一个简单的软件大体是如何进化而来（得到））
我们开发软件的过程原则和方法都被称为软件进化。从软件的初始开发到维护和更新，直到开发出满足预期要求的产品；这一过程都是软件进化的过程。结束点就是达到要求。

上software evolution的图片

进化的过程无非就是重复：
**搜集需求、设计原型、得到反馈后进行更改需求、开发、测试、上线**、再重复。

在给用户开发软件完成后，客户会因为先进的技术和不断变化的需求要求做出改变。这时候又开始软件进化的过程。重新开始是耗时耗力的。因此，在实际工作中应当留存项目代码一段时间。确保用户再次联系提出新要求时能够拿出原项目的工程文件继续更新新功能和完善内容。

### 软件不断进化会导致什么？
1. 会持续变化
2. 会增加复杂性
3. 必须保持对软件的熟悉度，否则会忘记之前开发软件时的思路和代码内容代表什么意思。
4. 软件的规模会持续增长；
5. 软件系统的质量如果不严格维护的话会下降
6. 进化到后期要有多回路和多层次的反馈系统，不然规模大了后期很麻烦。
7. 需要维持组织的稳定性。软件规模不断进化。大的组织成员或其他调动会影响项目的开发。也就是我们所说的原班人马。新的人员对整个软件的熟悉程度和开发思路不能很好的掌握。


# 实际在软件开发的生命周期（SDLC）

完整的生命周期框架如下：
上图

- 沟通：与用户沟通需求、收集需求
- 可行性研究：在财务、时间、和技术上考虑是否可行；
- 系统分析：确定路线、提出适合项目的软件模型。
- 软件设计：设计原型图、画逻辑图、流程图、数据图；
- 编码：将设计的东西用代码实现出来；
- 测试：与编码同时进行，测试程序是否正确；可以分模块测试；
- 一体化：将写好的内容与外部所需要的如：数据库、服务器、其他程序集成后打包；
- 运维：软件上线、交给用户使用，开发人员维护软件的状态；

## 什么是软件范式（设计、开发软件的方法和步骤）
上图

### 整个软件的工程范式（大的方向）
- 收集需求
- 设计
- 编程
### 设计时候的范式
- 设计（画原型图、画交互图）
- 维护（考虑设计的东西方不方便后期维护）
- 编程（考虑设计的内容能否被开发团队实现）

### 编程时候的范式
- 编码（考虑前期设计师设计的原型图如何通过编码实现）
- 测试（对编写完的程序进行测试）
- 整合（将程序本体和其他需要用到的库、数据、文档、其他内容整合到一个里边进行打包。）



## 软件开发的范式模型（在系统分析时确定）在软件开发的过程中可以用到哪些已有的方法和步骤模型？
### 瀑布模型
线性的、逐步完成。做好一步做下一步；
上图；
如果你设计和研发过类似的软件，那么适合使用此模型；


### 迭代模型
上图：
重复开发过程，完善每一个周期的内容；
相当于用一个开发的生命周期开发并上线。在需要更新的时候再重做项目的每个周期，完善每个周期。
很消耗资源。

### 螺旋模型

增加了风险考虑。并且一次迭代开发完就要去考虑下一次迭代。

### bigbang模型
计划不明确、想做什么做什么；不适合大型软件项目制作，适合学习和试验。



## 软件测试的范式模型（在软件开发的过程中可以用到哪些已有的方法和步骤模型？）
### V型 （用来测试的模型）





# 软件项目管理
## 为什么需要管理？
确保和调配资源。达到时间、质量、开支的的平衡；
上图

## 谁来管理？软件项目经理
### 是什么
是承担执行软件项目责任的人。可能不会直接参与开发和生产，但是他控制和管理生产涉及的活动；担任项目的发言人；分析每个阶段的风险；采取措施避免或解决问题

### 干什么
#### 管理人员和沟通
管理人力资源、保持成员之间的沟通；选择合适的通信工具，让成员之间进行规划、进度的分享和反馈；
#### 管理活动
##### 项目的计划
（做什么？怎么做？每个人做什么）

##### 管理项目计划

- 划分范围：项目要做什么，不要做什么。将项目分成多个较小的部分方便管理；验证范围是否可行，如果不做那个客户是否满意，如果做了那个客户是否会增加预算；如果内容做多了或者做少了要及时更改成员的工作范围；拿了多少钱，该做什么不该做什么；
-  估算项目：
	- 估算软件规模（通过代码行、功能点或者根据经验）；
	- 估算每个人的工作量，划分制作软件的工时；
	- 估算项目的完成时间。可以划分为小任务后按天或者小时安排；
	- 估算成本；
		- 可以参考：软件大小、质量、硬件（内部的）；许可证、额外的软件或者工具；服务器支持等等（不是我们公司做的外部的）
- 安排任务：尽可能将项目划分小块，将相关联的功能或者模块一起做；
- 划分时间：将时间划分为工作单元，规定小块任务的完成工作单元。（比如2小时为一个工作单元，为子项任务分配工作单元，或总时间）；规定整个项目的总完成时间；

- 安排资源：分配和调度资源；创建小团队，为每个团队成员分配责任；确定每个团队使用的设备数量、和其他资源；
- 确定进度：将某些子任务块做完后设立一个里程碑，方便任务分阶段进行；


#### 管理项目风险
- 确定整个项目可能发生的风险；
- 将风险分为高中低；
- 确定项目开始后每个阶段可能得风险；
- 确定潜在风险；没有外部影响的情况下，代码是否有风险；


#### 监督项目执行和监控
- 看每个活动表是否完成
- 看每个成员的活动状态，是开发中、还是完成、还是离线。
- 看项目的里程碑进展；

#### 跟踪和控制项目变化过程
如果项目的需求需要变化、设计需要改动、开发需要变动；
要向上级或者高层申请，得到批准后确定启动项目变更；

项目变更：
- 标记外部用户或者内部人员的变更请求，确定下来后，记录下来；
- 验证变更是否可行，是否可以。批准
- 根据进度、成本、和所需的工作量确定变更请求的影响；
- 控制：如果分析后影响太大，需要请求高级主管部门的批准；不批准则拒绝
- 执行批准的请求；修订项目内容；
- 关闭，如果结项，就关闭请求口；


## 管理的工具
## 时间进度管理工具
### 甘特图
### PERT图
## 资源管理工具
### 资源直方图

## 代码管理工具
### github
### gitlab

## 看板


# 怎样才算一份好的产品软件
做成图表










