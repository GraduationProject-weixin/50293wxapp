# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50293wxappvue和微信小程序的校园自助打印系统+springboot

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


﻿**摘  要**

网络和科学技术的发展改变了人类的生活。科技的进步使计算机技术生活化，帮助人们的工作和生活。目前信息化成为主流，使人类进入新的文明社会。本系统是利用现代科技和网络开发的帮助网上预约打印的小程序，可以减少打印的排队时间，提高工作效率和帮助用户的信息查询。

本基于Vue和微信小程序的校园自助打印系统采用JAVA语言和微信小程序技术，数据库采用Mysql，运行软件为微信开发者工具。本系统实现了管理员和用户、店长三个角色的功能。管理员的功能为个人中心管理、用户管理、店长管理、打印店管理、打印服务管理、服务类型管理、预约打印管理等。用户的功能为查看打印店进行预约和了解打印服务和管理收藏信息等。店长可以管理打印店、打印服务和预约打印信息。本系统实现了网上预约打印的流程化管理，可以帮助工作人员的管理工作和帮助用户查询打印的相关信息，改变了用户打印的方式，提高了用户打印的效率。

关键词：打印预约；打印店管理；打印服务管理；微信小程序；Vue技术









**Abstract**

The development of network and science and technology has changed human life. The progress of science and technology makes computer technology life and helps people's work and life. At present, informatization has become the mainstream, making mankind enter a new civilized society. This system is a small program developed by using modern technology and network to help online reservation printing, which can reduce the printing queue time, improve work efficiency and help users' information query.

The campus self-service printing system based on Vue and wechat applet adopts Java language and wechat applet technology, the database adopts mysql, and the running software is a wechat developer tool. The system realizes the functions of administrator, user and store manager. The administrator's functions include personal center management, user management, store manager management, printing store management, printing service management, service type management, reservation printing management, etc. The user's function is to view the printing shop, make an appointment, understand the printing service and manage the collection information. The store manager can manage the printing store, printing service and reserved printing information. The system realizes the process management of online reservation printing, which can help the management of staff and help users query the relevant information of printing, change the way of user printing and improve the efficiency of user printing.

**Keywords:** print reservation; Print shop management; Print service management; Wechat applet; Vue Technology






# **目  录**
[摘  要	1]()

[Abstract	2]()

[第1章 绪论	5]()

[1.1课题背景与问题来源	5]()

[1.2课题现状和研究意义	6]()

[1.3课题研究内容	6]()

[1.4论文结构安排	7]()

[第2章 系统分析	7]()

[2.1系统使用相关技术分析	7]()

[2.1.1JAVA语言介绍	7]()

[2.1.2微信小程序技术介绍	8]()

[2.1.3Mysql数据库	8]()

[2.1.4Vue技术介绍	9]()

[2.2系统可行性分析	9]()

[2.2.1系统技术可行性分析	9]()

[2.2.2系统经济可行性分析	9]()

[2.2.3系统操作可行性分析	10]()

[2.3系统性能分析	10]()

[2.4功能分析	11]()

[2.5系统操作流程分析	11]()

[第3章 系统设计	12]()

[3.1系统功能结构设计	12]()

[3.2数据库设计	13]()

[3.2.1数据ER图设计	13]()

[3.2.2数据库表设计	15]()

[第4章 系统详细实现	19]()

[4.1登录功能模块的界面实现	19]()

[4.2管理员操作界面的功能模块实现	20]()

[4.2.1个人中心管理功能模块的界面实现	20]()

[4.2.2用户管理功能模块的界面实现	21]()

[4.2.3打印店管理功能模块的界面实现	22]()

[4.2.4打印服务管理功能模块的界面实现	23]()

[4.2.5预约打印管理功能模块的界面实现	24]()

[4.2.6店长管理功能模块的界面实现	24]()

[4.3用户角色的操作界面实现	25]()

[4.4首页界面的操作功能实现	26]()

[4.5店长角色功能的界面实现	27]()

[第5章 系统测试	29]()

[5.1实例测试的研究与选择	29]()

[5.2测试环境与测试条件	29]()

[5.3功能测试	29]()

[5.3.1用户登录功能的测试	29]()

[5.3.2用户预约功能的测试	30]()

[5.3.3店长预约管理功能的测试	32]()

[5.4测试结果	33]()

[结束语	34]()

[参考文献	35]()

[致  谢	36]()










**第1章 绪论**
## **1.1课题背景与问题来源**
随着信息化时代的到来，方便了人们的生活。各个行业都离不开小程序技术的辅助。小程序技术可以实现信息的快速处理，帮助人们减少工作压力，采用小程序技术的管理系统对于信息安全的保证更为可靠。管理系统对于复杂的信息更能体现优势，弥补了人工管理的缺点。虽然现在很多的企业和商家都已使用了相关的管理系统，但采用的大多都还是人工+计算机管理的方式进行工作的管理。这种方式还是需要大量的人工参与，不能彻底解放工作人员的“双手”，对于减轻工作压力非常有限。特别对于信息的查询和统计，都还是需要人工进行多次核实才可以完成，非常浪费时间和体力，经常需要工作人员加班，为企业带来成本的增加。不能适应科学技术的发展。

打印是学生在学习生活中最常见的事。特别是在论文写作期间、考试期间等需要打印的学生非常多，造成需要排队。为了实现打印店的分流以及减少人群接触网上预约打印的用户非常多，工作人员的压力也非常大。如果没有有效的工作流程和办公工具会造成工作的出错，一旦工作出错影响打印店的生意，发生矛盾。所以网上预约打印的工作需要严谨，对于信息的管理尤为重要，需要更为安全可靠的办公工具来帮助工作。本基于Vue和微信小程序的校园自助打印系统由此开发，基于Vue和微信小程序的校园自助打印系统可以充分信任、放心使用。
## **1.2课题现状和研究意义**
小程序技术的发展也对人们提出了更高的要求，经济的提高相对应着工作的压力提高。我国目前正处在网络发展的快速时期，要求网络可以为人们做出更多的服务。现在，我国的企业、公司等都还是采用半人工的工作方式，也就是在工作中加入小程序技术但还是大部分以人为主导。这种现象充分反映了当代人们对小程序技术的不信任。造成这种现象的主要原因是一些办公软件的功能不完善、操作流程不友好、信息安全没有保证。

进入本世纪后，管理系统进一步发展。国家大力支持科技，对网络安全提供了保障。管理信息可以处理复杂的信息从而提高用户的工作效率，减少失误。所以本基于Vue和微信小程序的校园自助打印系统的开发非常有意义，本系统里的信息大致可以分为打印服务信息、打印店信息、收藏信息、店长信息、用户信息、预约信息等。把这些信息交给计算机处理非常安全，对于信息的搜索也更为快速。
## **1.3课题研究内容**
`   `本系统主要研究的内容为用户相关信息和管理员相关信息、店长相关信息。和管理员相关的信息有用户信息、店长信息，包括审核用户、店长信息和删除用户、店长信息，打印店信息，包括审核打印店和删除打印店。和用户相关的信息有预约信息和收藏信息。和店长相关的信息为打印店信息和预约信息、打印服务信息。本系统的功能非常全面，信息也非常安全，对于各类信息的存储也非常合理，可以帮助网上预约打印的管理工作。
## **1.4论文结构安排**
本论文的结构分为绪论、系统分析、系统设计、系统实现和系统测试。对于论文结构的安排采用了系统开发的流程。

第1章绪论，在绪论中阐述系统开发的背景、现状和意义、内容；

第2章系统分析，在系统分析中从开发语言分析到可行性分析，加入系统流程分析和功能分析；

第3章系统设计，本部分内容为系统的规划；

第4章系统实现，把系统的设计转换到具体的实现中；

第5章系统测试，根据系统的实现进行测试，保证系统实现中没有错误。






**第2章 系统分析**
## **2.1系统使用相关技术分析**
### 2.1.1JAVA语言介绍
Java语言跟c++语言非常的相似，可以说是从c++上进行衍生出来的一个新型开发语言，他充分吸收了其他语言的优点，而避开了它们的缺点，使编程语言更加的简单，而且Java系统非常的小，摒弃掉了之前的运算符重载，然后造成的卡顿现象，然后添加了垃圾自动清理，增加了开发的简单和可靠性。当然了Java最大的特点是平台独立性，只要可以支持Java虚拟机环境，就可以直接运行所有程序，而且还是面向对象开发的技术，有很好的封装行，采用了动态编码技术，可以使程序更好的呈现。可以多线程进行运行，用户随时可以加入新的 实例然后不影响整体程序执行，使开发更有灵活性，因为Java是在公共密钥技术上进行建立开发的，所以也有一定的安全保障，除此之外，还有一定的跨平台性，可扩展性等优点，可以和不同的操作环境进行互联共享，所以Java语言是目前使用最广泛的一个语言开发技术。
### 2.1.2[微信](https://baike.baidu.com/item/%E5%BE%AE%E4%BF%A1/3905974)小程序技术介绍
[微信](https://baike.baidu.com/item/%E5%BE%AE%E4%BF%A1/3905974)小程序，[小程序]( t )的一种，英文名Wechat Mini Program，是一种不需要下载安装即可使用的[应用](https://baike.baidu.com/item/%E5%BA%94%E7%94%A8)，它实现了应用“触手可及”的梦想，用户扫一扫或搜一下即可打开应用。全面开放申请后，主体类型为企业、政府、媒体、其他组织或个人的开发者，均可申请注册小程序。微信小程序、微信订阅号、微信服务号、[微信企业号]( t )是并行的体系。微信小程序是一种不用下载就能使用的应用，也是一项创新，经过将近两年的发展，已经构造了新的微信小程序开发环境和开发者生态。微信小程序也是这么多年来中国IT行业里一个真正能够影响到普通程序员的创新成果，已经有超过150万的开发者加入到了微信小程序的开发，与我们一起共同发力推动微信小程序的发展，微信小程序应用数量超过了一百万，覆盖200多个细分的行业，日活用户达到两个亿，微信小程序还在许多城市实现了支持地铁、公交服务。微信小程序发展带来更多的就业机会，2017年小程序带动就业104万人，社会效应不断提升。
### 2.1.3Mysql数据库
Mysql数据库是一个开源的数据库产品，功能非常的强大，可以运行在各个操作系统上面，而且支持各种不同的编程语言，数据库是用来存储和管理数据信息的一个仓库，都是通过api进行创建，然后实现数据信息的访问，管理和搜索等，现在的数据库都是采用的关系型数据库，就是建立在关系模型之上的，通过几何代数等数学方式来进行处理数据，存储的数据通常是以表格的形式，就是看起来是一个电子表格一样，然后分为不同的列和行等，还需要设置数据的主键和外键等，还要使用索引，可以快速的查找和访问数据，然后才能生成一个完整的数据库。
### 2.1.4Vue技术介绍
Vue 是 [iOS](https://baike.baidu.com/item/iOS/45705) 和 [Android]( t ) 平台上的一款 Vlog 社区与编辑工具，允许用户通过简单的操作实现 Vlog 的拍摄、剪辑、细调、和发布，记录与分享生活。还可以在社区直接浏览他人发布的 Vlog，与 Vloggers 互动。随着[手机摄像头](https://baike.baidu.com/item/%E6%89%8B%E6%9C%BA%E6%91%84%E5%83%8F%E5%A4%B4/2678025)的发展，越来越多的人开始使用手机拍照和摄像。摄像一般来说要比拍照门槛高，但是视频传播的信息量又远大于照片。Vue 就诞生在这样的背景下，希望用拍照一样简单的操作，帮助用户在手机上拍摄精美的短视频。
## **2.2系统可行性分析**
系统是否可行决定着系统是否要开发，分析系统的可行性通常从系统的技术性、经济性和操作性分析。系统可行性分析是非常重要的一步，不可缺少。本系统为基于Vue和微信小程序的校园自助打印系统，所以在系统可行性分析时需要充分考虑到使用用户和打印店的需求以及开发条件、配置、硬件环境等。
### 2.2.1系统技术可行性分析
`   `技术可行性一般从系统开发所使用的技术和系统运行所使用的软件进行分析。本系统在开发中采用JAVA语言和Mysql数据库。JAVA语言为动态的开发语言，支持多种平台，代码也非常健壮。使用JAVA语言开发的系统可以把代码单独拿出来用到其它平台上。Mysql数据库为小型的关系型数据库，支持JAVA，Android，PHP等语言，在安装和使用中非常简单。本系统在运行中采用微信开发者工具软件，微信开发者工具含有非常多的控件，可以使系统在调试中节省安装其它组件的时间。综合分析，本系统在系统可行性分析上是没有问题的。
### 2.2.2系统经济可行性分析
经济可行性分为系统的开发成本和运行成本以及售后维护成本。本系统在开发中不需要资金的支持，只需要电脑一台；本系统在运行中的成本也是电脑、手机一台。如今电脑、手机价格已平民化，电脑、手机的普及率已达到百分之八十；本系统在今后的维护中也仅需要一人就可以完成。综合分析，本系统的在经济可行性分析上也是没有问题的。
### 2.2.3系统操作可行性分析
`   `系统的操作可行性包括用户使用本系统的操作流程和界面的设计、布局。本系统在设计中大量调查了使用人员的习惯和审美，所有的功能都采用统一的风格方便用户使用。本系统的操作流程采用大众的操作习惯，并加入大量的提示框。比如在删除信息时，会提示“是否删除本条信息”的提示框，为用户做出指导。本系统在界面设计中采用了简单、大方的布局。综合分析，本系统在操作可行性上分析是没有问题的。

`    `本系统从技术可行性、操作可行性和经济可行性三方面分析得出，本系统的实现可行，是可以为用户带来工作帮助，非常有意义的。
## **2.3系统性能分析**
目前很多的预约打印中都使用了计算机技术的管理系统，管理员在计算机中录入用户的预约然后进行时间的安排。打印店的内部人员都可以使用此类管理系统，方便了打印店内部工作人员的工作，但用户想要了解服务信息、打印信息等还必须找到专业负责人员进行了解，非常不方便。而且有时候对于一些特殊信息还是采用纸张记录的方式进行保存，这种方式非常容易出错，造成工作失误。

本系统可以把用户加入进来，用户可以随时了解信息，清楚预约情况。为了可以使系统更好的实现和正确的设计，在设计时就需要考虑到：

（1）在设计本系统的功能界面时，需要考虑到用户的需求，多方位调查用户的操作习惯和操作需求，总结出最适合用户使用的操作功能界面。当然在设计中也要充分考虑到自己的水平，在自己能力范围内尽可能的满足用户的需求；

（2）为了提高系统的使用率和实用性，在系统的功能设计中要考虑到方方面面，调查不同角色用户的工作需求，总结出功能完善的系统。对于代码的编写也要求减少废弃代码来保证系统的运行和系统的大小；

（3）最重要的一点为信息安全，本系统里的信息涉及到个人隐私和平台隐私，所以系统在设计中需要采用安全机制；

（4）系统代码的健壮性，随时时代的发展，人们的需求会不断的发生改变。这时候就需要对系统进行扩展，在扩展中就需要考验系统的代码健壮性。在经过多次修改后，系统的代码还可以正确使用，为系统的扩展和升级提供保障。本系统采用JAVA语言进行代码编写，JAVA语言的代码支持多种环境，并且可以封装，可以直接移植到其它环境中使用。所以本系统的代码非常健壮。
## **2.4功能分析**
`    `在系统实现时先进行功能的分析，可以保证系统功能实现的完整性。如果没有经过功能分析直接进行实现，难免不会在系统完成后发现需要进行完善，造成需要再次开发。功能分析可以降低系统的开发成本，提高开发效率。

`   `本系统是针对校园自助打印开发的工作管理系统，包括到所有的工作内容。可以使自助打印的工作合理化和流程化。本系统包括手机端设计和电脑端设计，有界面和数据库。本系统的使用角色分为管理员和用户、店长三个身份。管理员可以管理系统里的所有信息。店长可以发布服务信息和查询用户的预约信息。用户可以浏览打印服务和打印店、预约打印以及管理预约信息、收藏信息。
## **2.5系统操作流程分析**
`   `想要系统可以正确的运行就需要良好的操作流程。本系统的主要功能是对校园自助打印日常工作的管理，包括打印服务信息、打印店信息、预约信息、用户信息、店长信息等。本系统的操作流程如下图2.1所示：

![](/md/blog.001.png) 

图2.1系统操作流程图











**第3章 系统设计**
## **3.1系统功能结构设计**
`   `本系统的结构分为管理员和用户、店长。本系统的功能结构图如下图3.1所示：

![](/md/blog.002.png)

`  `图3.1系统功能结构图
## **3.2数据库设计**
`   `本系统为小程序类的预约平台，所以对信息的安全和稳定要求非常高。为了解决本问题，采用前端界面展示，后端数据处理的方式进行设计。在后端数据的存储中采用Mysql数据库进行设计。数据库设计分为ER图设计和数据库表设计。
### 3.2.1数据ER图设计
本系统中的数据种类非常多，想要把数据都有效的关联起来就需要注意数据之间的联系。因为数据之间都有联系，所以在数据库的操作中不能任意的删除，如果删除了一方的数据会造成系统的出错。

本系统中的数据有用户信息、管理员信息、预约信息、打印店信息和打印服务信息等。

1. 管理员信息的ER图如下图3.2所示：

![](/md/blog.003.png)

图3.2管理员信息ER图

(2)用户信息ER图如下图3.3所示：

![](/md/blog.004.png)

图3.3用户信息ER图

（3）打印店信息ER图如下图3.4所示：

![](/md/blog.005.png)

图3.4打印店信息ER图

（4）打印服务信息ER图如下图3.5所示：

![](/md/blog.006.png)

图3.5打印服务信息ER图

（5）预约信息ER图如下图3.6所示：

![](/md/blog.007.png)

图3.6预约信息ER图
### 3.2.2数据库表设计
数据库表的设计质量关系着系统的运行是否稳定，一个好的数据库表可以保证系统数据的正确处理，数据库表中设计了数据的分类和主外键、长度等信息。根据系统的ER图设计中本系统的数据库表有管理员信息表、打印店信息表、预约信息表、打印服务信息表、用户信息表等，具体的表详情如下表3.1－3.11所示：

表3.1 config


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|name|varchar|100|||||否|||
|3|value|varchar|100|||||是|||
表3.2 dayindian


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|dianzhangzhanghao|varchar|200|||||是|||
|4|dianpumingcheng|varchar|200|||||是|||
|5|dianpudizhi|varchar|200|||||是|||
|6|dianzhangxingming|varchar|200|||||是|||
|7|lianxishouji|varchar|200|||||是|||
|8|dianputupian|varchar|200|||||是|||
|9|zhuyingyewu|varchar|200|||||是|||
|10|yingyeshijian|varchar|200|||||是|||
|11|dianpujianjie|longtext||||||是|||
表3.3 dayinfuwu


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|fuwumingcheng|varchar|200|||||否|||
|4|fuwufengmian|varchar|200|||||是|||
|5|fuwuleixing|varchar|200|||||否|||
|6|zhizhangleixing|varchar|200|||||否|||
|7|fuwujiage|varchar|200|||||是|||
|8|zhuyishixiang|varchar|200|||||是|||
|9|fuwuxiangqing|longtext||||||是|||
|10|dianzhangzhanghao|varchar|200|||||是|||
|11|dianpumingcheng|varchar|200|||||是|||
|12|lianxishouji|varchar|200|||||是|||
表3.4 dianzhang


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|dianzhangzhanghao|varchar|200|||||否|||
|4|mima|varchar|200|||||否|||
|5|dianpumingcheng|varchar|200|||||否|||
|6|dianpudizhi|varchar|200|||||否|||
|7|dianzhangxingming|varchar|200|||||是|||
|8|xingbie|varchar|200|||||是|||
|9|youxiang|varchar|200|||||是|||
|10|lianxishouji|varchar|200|||||是|||
|11|xiangpian|varchar|200|||||是|||
表3.5 fuwuleixing


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|fuwuleixing|varchar|200|||||否|||
表3.6 news


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|title|varchar|200|||||否|||
|4|introduction|longtext||||||是|||
|5|picture|varchar|200|||||否|||
|6|content|longtext||||||否|||
表3.7 storeup


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|userid|bigint|20|||||否|||
|4|refid|bigint|20|||||是|||
|5|tablename|varchar|200|||||是|||
|6|name|varchar|200|||||否|||
|7|picture|varchar|200|||||否|||
|8|type|varchar|200|||||是|1||
|9|inteltype|varchar|200|||||是|||
表3.8 token


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|userid|bigint|20|||||否|||
|3|username|varchar|100|||||否|||
|4|tablename|varchar|100|||||是|||
|5|role|varchar|100|||||是|||
|6|token|varchar|200|||||否|||
|7|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|8|expiratedtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.9 users


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|username|varchar|100|||||否|||
|3|password|varchar|100|||||否|||
|4|role|varchar|100|||||是|管理员||
|5|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.10 yonghu


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_incr|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|zhanghao|varchar|200|||||否|||
|4|mima|varchar|200|||||否|||
|5|xingming|varchar|200|||||否|||
|6|xingbie|varchar|200|||||是|||
|7|youxiang|varchar|200|||||是|||
|8|shoujihaoma|varchar|200|||||是|||
|9|xiangpian|varchar|200|||||是|||
表3.11 yuyuedayin


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|fuwumingcheng|varchar|200|||||否|||
|4|fuwuleixing|varchar|200|||||否|||
|5|zhizhangleixing|varchar|200|||||否|||
|6|fuwujiage|varchar|200|||||是|||
|7|zhuyishixiang|varchar|200|||||是|||
|8|dianzhangzhanghao|varchar|200|||||是|||
|9|dianpumingcheng|varchar|200|||||是|||
|10|lianxishouji|varchar|200|||||是|||
|11|dayintupian|varchar|200|||||是|||
|12|dayinneirong|varchar|200|||||是|||
|13|zhanghao|varchar|200|||||是|||
|14|xingming|varchar|200|||||是|||
|15|xiadanshijian|datetime||||||是|||
|16|sfsh|varchar|200|||||是|否||
|17|shhf|longtext||||||是|||
|18|ispay|varchar|200|||||是|未支付||
|19|userid|bigint|20|||||是|||













**第4章 系统详细实现**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       
## **4.1登录功能模块的界面实现**
`   `在系统调试运行后，可以进入本界面，本界面是最基本的功能，可以保证系统的安全，采用验证的安全机制进行设计。在本界面里可以看到账号和密码的输入框。本系统中的登录权限为普通用户。必须三种信息都正确才可以验证成功进入到对应的操作界面。系统的登录功能模块的实现界面如下图4.1所示：

![](/md/blog.008.png)

图4.1系统登录功能的实现界面
## **4.2管理员操作界面的功能模块实现**
### 4.2.1个人中心管理功能模块的界面实现
`    `本功能的设计可以保证管理员账号的安全，使用本功能可以修改管理员的登录密码。管理员修改密码功能模块的实现界面如下图4.2所示：

![](/md/blog.009.png)

图4.2管理员修改密码功能的实现界面
### 4.2.2用户管理功能模块的界面实现
本功能可以实现用户信息的查询和删除，管理员添加用户信息功能填写正确的信息就可以实现用户信息的添加，点击用户信息管理功能可以看到系统里所有用户的信息，在添加用户信息的界面里需要填写姓名信息，当信息填写不正确就会造成用户信息添加失败。管理员管理用户信息功能的实现界面如下图4.3所示：

![](/md/blog.010.png)

图4.3管理员管理用户信息的实现界面
### 4.2.3打印店管理功能模块的界面实现
打印店可以使用户更好的了解店铺信息。打印店信息管理的流程为，管理员点击打印店信息管理功能，查看打印店信息，点击打印店修改功能，输入打印店信息然后点击提交按钮就可以完成打印店信息的修改。管理员查询打印店信息的实现界面如下图4.4所示：

![](/md/blog.011.png)

图4.4管理员查询打印店信息的实现界面
### 4.2.4打印服务管理功能模块的界面实现
打印服务可以帮助用户了解服务内容，管理员负责审核打印店发布的打印服务。管理员查询打印服务信息功能的实现界面如下图4.5所示：

![](/md/blog.012.png)

图4.5管理员查询打印服务信息的界面实现
### 4.2.5预约打印管理功能模块的界面实现
预约打印信息属于本系统里的核心数据，管理员可以对预约打印的信息进行查询。本功能设计的目的可以使预约打印进行及时的安排。管理员查询预约打印信息的实现界面如下图4.6所示：

![](/md/blog.013.png)

图4.6管理员查询预约打印信息功能的实现界面
### 4.2.6店长管理功能模块的界面实现
`    `管理员可以查询店长信息，可以进行修改删除。管理员查询店长信息的实现界面如下图4.7所示：

![](/md/blog.014.png)

图4.7管理员查询店长信息的实现界面
## **4.3用户角色的操作界面实现**
用户可以查看自己的预约和修改自己的资料并管理收藏信息。用户角色的操作界面的实现效果如下图4.8所示：

![](/md/blog.015.png)

图4.8用户操作界面的实现效果
## **4.4首页界面的操作功能实现**
在首页里可以看到管理员添加和管理的信息，用户可以在首页里进行打印的预约和打印店信息的了解。首页界面的实现如下图4.9所示：

![](/md/blog.016.png)

图4.9首页界面的实现效果
## **4.5店长角色功能的界面实现**
店长可以发布打印店信息和打印服务信息以及管理预约打印。实现界面如下图4.10所示：

![](/md/blog.017.png)

图4.10店长角色的功能实现界面






















**第5章 系统测试**
## **5.1实例测试的研究与选择**
`   `系统测试分为黑盒测试和白盒测试。白盒测试主要针对复杂大型的项目，需要多人配合才能实现，白盒测试主要从系统的逻辑方面进行测试。黑盒测试针对功能性测试，是检验系统的功能是否正确的测试方法，黑盒测试多用于小型简单的项目中。本系统采用黑盒测试的方法进行测试。通过数据的输入来检验系统的功能。

`   `在系统测试时需要先制定测试方案，在测试中把测试过程和测试结果都记录下来，测试完成后可以进行对比和分析，总结系统的问题和进行修改。系统测试是非常重要的一步，系统测试可以保证系统的正确也是验证系统正确的唯一手段。如果系统没有经过测试就投入使用会造成用户工作的严重失误并给编程人员带来负面影响。
## **5.2测试环境与测试条件**
本系统的测试环境为本人的电脑。本人的电脑为华为笔记本，安装的操作系统为windows10。运行软件为微信开发者工具和Mysql。先把系统的数据库进行附加，然后打开本系统进行调试运行，运行成功后进入正式的测试。
## **5.3功能测试**
本系统的主要功能为用户登录、用户预约、管理员管理预约信息。
### 5.3.1用户登录功能的测试
对用户登录功能的测试采用输入正确的账号和密码进行登录和输入错误的账号或者错误的密码进行登录以及输入正确的账号和密码进行登录。通过上述情况进行用户登录的测试发现，用户登录功能可以正确运行，用户通过登录后可以进入正确的操作界面，用户登录功能的测试界面如下图5.1所示：

![](/md/blog.018.png)

图5.1用户登录功能的测试界面
### 5.3.2用户预约功能的测试
对于用户预约功能的测试采用用户选择打印店进行预约，填写正确的预约信息，预约完成后，查看预约记录和用户选择打印店进行错误预约，预约完成后，查看预约结果。用户预约功能的测试界面如下图5.2所示：

![](/md/blog.019.png)

图5.2用户预约功能的测试界面

用户登录到系统中查预约记录信息的测试界面如下图5.3所示：

![](/md/blog.020.png)

图5.3用户查看预约记录信息的测试界面
### 5.3.3店长预约管理功能的测试
`   `对于店长预约管理功能的测试采用店长选择用户预约信息后进行审核，审核操作后，查看审核结果，用户登录后查看预约信息。店长预约管理功能的测试界面如下图5.4所示：

![](/md/blog.021.png)

图5.4店长查询预约信息的测试界面
## **5.4测试结果**
`   `通过对系统的测试发现，用户可以正确登录，用户预约后，用户可以查询到预约记录信息，店长审核预约信息后，用户可以查看到相关的审核信息。可见，本系统的功能是正确的。系统中还有很多的功能，本论文中只对部分功能进行了阐述。




















**结束语**

本系统通过JAVA语言Mysql数据库进行设计，完成了基于Vue和微信小程序的校园自助打印系统的实现。本系统可以帮助管理员和用户、店长的需求。用户可以预约、收藏打印店。管理员可以管理系统里的打印服务信息、店长信息和预约打印信息等。店长可以管理打印店信息、打印服务信息和管理预约打印信息。本系统可以实现网上预约打印工作的流程化管理，可以提高工作效率和帮助用户的信息查询。

本次设计通过系统分析、系统设计和系统实现、系统测试的步骤顺利完成。本人通过参考相关的网站和去图书馆查找资料设计了本次基于Vue和微信小程序的校园自助打印系统。功能相对完整、操作流畅，界面友好。本次设计让我对JAVA语言有了更深的认识，系统的学习了系统开发的过程。在设计中也遇到了很多的问题，通过我的不断努力问题也都得到了解决。本次设计锻炼了我的学习能力和解决问题的能力，让我明白了编程的辛苦，通过本次设计让我印象最深的为系统测试。系统测试让我认识到自己认为最简单的问题往往是最容易出错的地方。本基于Vue和微信小程序的校园自助打印系统还有很多的问题，因为个人能力和时间的问题没有继续完善，今后我会继续努力学习。本次设计也让我对未来充满信心。








**参考文献**

[1]傅伟,唐润琮,葛竹春.基于微信小程序的生鲜食品订购平台设计与实现[J].电脑编程技巧与维护,2022(04):76-79.DOI:10.16184/j.cnki.comprg.2022.04.029.

[2]杨迎.Java语言异常处理机制的分析[J].电子技术,2022,51(03):42-43.

[3]莫静容.“Java程序设计”课程教学改革[J].西部素质教育,2022,8(05):159-162.DOI:10.16681/j.cnki.wcqe.202205049.

[4]镇鑫羽,景琴琴.Java语言程序设计的教学实践[J].集成电路应用,2022,39(02):256-257.DOI:10.19339/j.issn.1674-2583.2022.02.111.

[5]杜凯.JAVA编程语言在计算机软件开发中的应用研究[J].软件,2022,43(01):92-94.

[6]孙辉中.JAVA编程语言在计算机软件开发中的应用[J].网络安全技术与应用,2022(01):49-50.

[7]刘学玉.JAVA编程语言在计算机软件开发中的应用[J].电子技术与软件工程,2022(01):57-60.

[8]刘天元,夏明.微信小程序开发与运用[J].电子世界,2021(23):206-207.DOI:10.19353/j.cnki.dzsj.2021.23.091.

[9]陈帅.微信点餐系统小程序的设计与实现[J].电子技术与软件工程,2021(24):30-31.

[10]李想,张玉军,余谨,杨维昊.资讯类微信小程序的设计与开发[J].科学技术创新,2021(31):106-108.

[11]Qiuying Han,Xiuye Yin. Application of Java Programming Language in Computer Software Development[J]. International Journal of Computational and Engineering,2020,5(4).

[12]Yangyang Jiang,Jiang Yangyang. Research on Application Value of Computer Software Development in Java Programming Language[J]. Journal of Physics: Conference Series,2020,1648(3).

[13]项靖,赵陈萍.基于微信小程序的云打印系统设计[J].中国新技术新产品,2020(13):38-39.DOI:10.13612/j.cnki.cntp.2020.13.015.

[14]刘羽张,张祎格,翟欣彤,闫博芸,李恩喆.校园自助打印系统的设计与实施——以中国民航大学为例[J].智库时代,2020(11):136-137+208.

[15]罗淑娴.高校图书馆一卡通自助打印复印服务实践[J].侨园,2019(11):86.

[16]郑显玲,汤雪姣.微信小程序助力图书馆学科服务[J].才智,2019(29):236-237.

[17]姚立敏.浅析浙江大学成绩自助打印系统[J].考试周刊,2017(42):139+141.























**致  谢**

很快就度过了美好的大学时光，学习了计算机专业各方面的知识，对老师渊博的学识深深的佩服，老师不光教会了我们专业的知识，还教会了我们很多做人处事的道理，所以在这毕业之际，要深深的要各位老师表示感谢。还要感谢我的答辩指导老师，在整个毕业设计的过程中，给与了我很大的帮助和指导，从选题阶段到写任务书，到设计的实现和最终的完成，给我提供了好多宝贵的意见，而且在我遇见难题的时候及时的给我帮助，如果没有老师的辅导，我相信也不能这么顺利的完成我的设计。老师严谨的教学态度，是我们不断学习和前进的榜样。我一定要好好学习来回报我的母校，回报我的老师，老师，你辛苦了。最后还要感谢陪伴我一起成长一起学习的同学，因为有了你们，大学生活才变的多姿多彩，让我们一起努力，一起加油，共同开创更美好的明天。

6











