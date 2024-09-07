# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0488springboot七彩云南文化旅游网站的设计与实现pf

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=86)


# 第1章 绪论
## 1.1选题动因
当前的网络技术，软件技术等都具备成熟的理论基础，市场上也出现各种技术开发的软件，这些软件都被用于各个领域，包括生活和工作的领域。随着电脑和笔记本的广泛运用，以及各种计算机硬件的完善和升级，市面上的电脑和笔记本的性能都得到提升，可以支持的软件也逐渐增多，因此，在计算机上安装软件来发挥其高效地信息处理的作用，则很受人们的青睐。对于七彩云南文化旅游网站信息来讲，通过手工形式处理，在面对庞大的信息数量时，就显得不适宜了，首先需要花费的时间比较多，其次数据出错率比较高，而且对错误的数据进行更改也比较困难，最后，检索数据费事费力。因此，为了解决上述问题，有必要建立七彩云南文化旅游网站，来规范七彩云南文化旅游网站信息管理流程，让管理工作可以系统化和程序化，同时，七彩云南文化旅游网站的有效运用可以帮助管理人员准确快速地处理信息。
## 1.2目的和意义
七彩云南文化旅游网站可以对七彩云南文化旅游网站信息进行集中管理，可以真正避免传统管理的缺陷。七彩云南文化旅游网站是一款运用软件开发技术设计实现的应用系统，在信息处理上可以达到快速的目的，不管是针对数据添加，数据维护和统计，以及数据查询等处理要求，七彩云南文化旅游网站都可以轻松应对。所以，七彩云南文化旅游网站的运用是让七彩云南文化旅游网站信息管理升级的最好方式。它可以实现信息处理的便利化要求，还可以规范信息处理的流程，让事务处理成为管理人员手中的一件简单事，而不是之前手工处理时的困难事。尽管七彩云南文化旅游网站具备较完善的功能，但是也需要管理人员利用闲暇时间提升自身素质以及个人能力，在操作七彩云南文化旅游网站时可以最大化运用七彩云南文化旅游网站提供的功能，让系统在满足高效率处理数据的同时，也能始终稳定运行，还可以确保数据的可靠性与数据处理的质量。
## 1.3论文结构安排
本文总共分为6个章节，每个章节都对本系统描述了不同的内容。接下来就对本文的研究内容进行阐述。

第1章：这个章节是论文的绪论部分。从选题的背景和意义的角度阐述即将开发的系统。

第2章：这个章节是技术介绍部分。从本系统需要运用的技术知识的角度阐述系统。

第3章：这个章节是系统分析部分。从分析系统可行性，分析系统功能和性能等角度阐述系统。

第4章：这个章节是系统设计部分。从系统功能结构的角度和数据库设计的角度阐述系统。

第5章：这个章节是系统实现部分。从系统功能模块运行效果的角度阐述系统。

第6章：这个章节是系统测试部分。从测试系统功能，系统测试方法的角度阐述系统。


# 第2章 开发环境与技术
开发七彩云南文化旅游网站需要搭建编程的环境，也需要通过调查，对各个相关技术进行分析，选取适合本系统开发的技术与工具。
## 2.1 MYSQL数据库
本课题研究研发的应用程序在数据操作里是难以预测的，而且常常产生变化。没有办法直接从word里写数据信息，这不但不安全，并且难以实现应用程序的功能。想要实现运用所需要的文件存储功能，就必定要选择专业数据库存储软件。大部分，应用程序达到的功能并不太繁杂，市场中所有关系数据库手机软件都能实现。但MySQL数据库，安装文件小，组装速度更快，使用方便，即便组装问题改进，不用再次安装操作系统，也不会影响电脑中第三方软件的运转，损耗网络资源少，最主要的是功能充分满足设计定位，因此最终选择MySQL数据库做为软件开发技术所需要的数据库。
## 2.2 Tomcat 介绍
刚开始学习Java语言的时候，是不知道还有Tomcat这些东西的，各种语法各种输出在控制台进行输出结果，当Java网站开发的时候就不可避免的学习到了Tomcat服务器。Tomcat准确的来讲不算是服务器，可以说是vue引擎或者一个容器，这些都是学术上或者原理上都比较贴切的，但是实际工作中Tomcat就是作为一个web服务器来用的，因为可以实现网站的发布和运行。因为工作原理的原因，Tomcat一般作为中小型企业和并发量并不突出的一种轻量级的服务器存在的，比如某些行业的应用系统，本身客户端就不多，需要的连接也不多，一般都用Tomcat的。Tomcat里面可以配置多个网站，配置文件后缀是config的文档，类似于XML的结构，比较清晰明了。每当Java发布新的版本的时候，Tomcat也会为了匹配Java的版本进行升级，目前Tomcat版本已经到版本10了。Tomcat标识是一只有点发黄的小猫咪，当Tomcat配置成功一般测试的时候能看到这个小猫咪就算是成功的，才能进行下一步的配置。Tomcat服务器在Java网站开发中还是挺合适的。
## 2.3 vue技术
vue技术可以让初学者尽快上手进行编写动态网站，不需要变成高级的Java编程人员才可以书写代码，从学习的效率还有编写的效率上都有很大的提升。让着重于网页开发者与着重于后台逻辑开发进行分离合作开发变成了一种可能，降低了学习成本，不需要考虑程序运行解释编译阶段的话，vue网页本身就可以理解成一个普通的Servlet。vue结构上面，主要分为两个方面，一个是专属的vue引擎，通俗的讲就是可以实现vue编译后运行解释的一个东西，另一个就是web服务器。vue运行编译需要vue引擎和web服务器进行配合以及相互协作，当然他们的分工也是很明确的，这样才可以真正的运行起来。vue容器和引擎有Tomcat，这个Tomcat其实也还有Apache静态解释代码的部分，虽然看起来运行效果差不多，但是其实是两个截然不同的工具，在文件系统里目录也是不一样的，当然如果有特殊需求也是可以进行特殊的配置的，配置上面还是比较灵活的。虽然Tomcat部署了网站之后就可以运行网页让客户访问，但是Tomcat也只是vue引擎而非web服务器。比如JRUN和Resin都算是vue引擎，而web服务器的职责比较单一，就是处理客户端请求还有返回给客户显示请求处理后的数据而已。vue引擎则可以运行纯HTML编写的网站，也可以运行vue编写的动态网站，在效率上也只是比单纯的web服务器而已，但是从纯web服务器无法运行动态网站上来讲，vue引擎在功能上还是强大了很多，提升一点点效率反而算不了什么，对于必须实现的功能这些要素上，选择了vue技术。
## 2.4 SpringBoot框架
在过去的两三年的Spring生态系统中，最令人兴奋的是Spring Boot框架。或许从取名上能够得知这一框架设计初心：快速开启Spring运用。因此Spring 实质上，Boot应用程序是一个根据Spring框架的应用程序。这是Spring“协议书先于配置”理论的良好实践物质。可以帮助开发者迅速、更有效地搭建根据Spring生态系统的应用程序。

Spring Boot有什么魔法？全自动配置、发展依靠、Actuator、命令行界面(CLI) 是Spring Boot最主要的四个核心特点，在其中CLI是Spring Boot的能选特点尽管功能齐全，却也引入了一套非传统的开发模型，因此本系列文章只注重别的三个特点。如标题，文中是本系列的第一部分，将为您开启Spring Boot大门口，关键为您进一步分析启动过程及全自动配置完成基本原理。把握这一部分主要内容，了解一些Spring框架的基本知识，也会让你游刃有余。
# 第3章 系统分析
用户的需求以及与本系统相似的在市场上存在的其它系统可以作为系统分析中参考的资料，分析人员可以根据这些信息确定出本系统具备的功能，分析出本系统具备的性能等内容。
## 3.1可行性分析
尽管系统是根据用户的要求进行制作，但是在确定制作前，有必要分析其可行性。
### 3.1.1操作可行性分析
开发本系统需要用到的工具，本人都比较熟悉，因此可以使用这些工具，完整开发七彩云南文化旅游网站。此外，七彩云南文化旅游网站在功能上，基本都是完成信息的处理，涵盖了添加，修改，删除等，而且操作者面对的都是各个功能操作界面，并不是编码后台，所以一般的使用者都可以通过操作界面轻松完成信息的加工处理。因此，本系统操作可行。
### 3.1.2经济可行性分析
开发本系统，并没有投入资金购买开发工具。因为使用的开发工具都是事先在百度上下载安装在本人电脑上的，随着软件开发技术的成熟，系统功能实现的编码也都模块化，很容易通过各大软件开发类网站获取，并通过小部分代码改动，运用到本系统中，这些都不需要资金投入，同时，本系统开发的结构选用B/S，成本可以忽略不计。
### 3.1.3技术可行性分析
本系统需要的软件包括Eclipse，Tomcat，Mysql等，这些工具都接触并使用过，至于JAVA，B/S，vue，Html等技术，图书馆都有对应的书籍可以参考学习，加上平时课堂上学习的编程小项目对这些技术都有讲解，另外，本人也从课程设计作业中锻炼了编程能力。所以在技术上，可以完成七彩云南文化旅游网站的编程开发。

通过上面的分析，已经确定了本系统在经济上的可行，本系统在技术上的可行，本系统在操作上的可行。由此，可以得出在目前的条件下，对于七彩云南文化旅游网站的设计与实现是可以进行下去的。
## 3.2系统流程分析
本系统在处理数据时，其内部的操作逻辑也需要使用相应的工具进行展示。

在本系统的数据录入页面，对于操作者提供的每条数据都有相应的检验规则，比如数据信息不能有非法字符，或者本来应该是汉字的数据，不能用字母代替，还有对数据内容的长度等进行规范，这样的可以确保数据准确性的检验规则，在编码时，就提前编写好了。数据添加的流程见下图。如果数据已经保存进入数据库，则说明操作者提供的数据内容和格式都是符合要求的。

![](/md/blog.001.png)

图3.1 添加信息流程图

很多时候，面对系统中的大量数据，难免会发现一些错误，因此需要及时纠正错误，本系统也提供数据后期的修改功能，其流程见下图。但是更新的数据也需要通过数据有效性检验。能够最终写入数据库则说明修改的数据是符合要求的。

![](/md/blog.002.png)

图3.2 修改信息流程图

面对数据库里面大量数据，在系统的前台，要想快速获取需要的信息，就需要使用查询功能。其流程见下图。该功能需要操作者提前输入关键词，当系统的后台数据库保存了与关键词匹配的数据时，就会及时显示出来，整个过程耗时很短。

![](/md/blog.003.png)

图3.3 查询信息流程图
## 3.3系统性能分析
分析七彩云南文化旅游网站对于性能的需求主要还是从下面的5个角度来分析，它们分别是系统的实用性，系统的适应性，系统的易操作性，系统的安全性和系统的易维护性。

性能需求一：系统的实用性，本系统主要是让管理人员集中处理相关信息，可以提供方便快捷的信息添加，信息编辑等操作。在提高信息管理人员的工作效率的同时，也可以降低管理成本，并大大减少管理人员日常繁琐的工作量。

性能需求二：系统的适应性，本系统对于运行环境的要求并不高，可以被广泛运用在生活中。因为使用者只要在日常使用的计算机，或者是随身携带的笔记本上搭建运行环境都能运行本系统，另外系统提供的基础功能包括添加，修改等都能随时操作。

性能需求三：系统的易操作性，本系统提供的功能跟同类型系统一样，也具备简单的增删改操作，操作流程的逻辑也符合广大使用者的使用需求，使用者使用本系统管理数据会非常顺手。

性能需求四：系统的安全性，本系统在数据保存与管理上安全系数要达标，在设计与编码阶段，通过对用户进行权限分配，把系统的功能依照不同用户的角色进行分配，在首次进入系统时，通过编写安全验证的代码模块，引导不同用户进入不同的操作界面。还可以对用户基础信息包括登录的账号密码等进行加密保存，可以利用当下常用的技术成熟的MD5加密技术实现。

性能需求五：系统的易维护性，本系统在后期运行中，会根据使用者的操作，产生许多数据信息，为了便于维护，就要求这些数据可以通过工具从数据库中导出来，对于一些阶段性数据，可以进行批量删除，以此达到轻负荷处理数据的目标，让本系统可以变得更加轻盈。
# 第4章 系统设计
市面上设计比较好的系统都有一个共同特征，就是主题鲜明突出。通过对页面简洁清晰的布局，让页面的内容，包括文字语言，或者视频图片等元素可以清晰表达出系统的主题。让来访用户无需花费过多精力和时间找寻需要的内容。
## 4.1界面设计原则
一般来说，大部分用户使用系统，有些是想从系统中获取需要的信息，有些则是使用系统提供的服务。所以，为了改善用户体验，提高系统的使用率，在对系统界面设计时，需要按照下面的原则进行。

第一点，对用户进行分析，了解用户使用系统的目的，以及使用系统的方式，考虑大部分用户的阅读习惯，设计Z字形或F型结构可以方便用户获取信息。

第二点：设计有效的导航，这个包括每个页面上都有导航条的显示，有时也可以在页面的底部设计导航条，当用户进入具体页面时，要设计相应的位置提示，在页面中比较特殊的位置，需要设计返回链接，可以返回上个页面，也可以返回首页等。

第三点：对整个系统要运用统一的设计方案，包括色彩方案的一致性，页面模板的相似性等，对相同操作和专业术语的描述在整个系统中也应该保持一致。

第四点：设计的界面要保证传达的内容清晰准确。要避免在同一个页面设计非常多的内容，另外可以准确对系统内容进行分类，把页面中用户视觉集中的位置，用来显示重要信息。

作为初学者，并没有那么多的设计经验，但是可以运用上面提到的界面设计原则设计出比较好的系统，可以让用户产生良好的使用体验。
## 4.2功能结构设计
为了让系统的编码可以顺利进行，特意对本系统功能进行细分设计，设计的系统功能结构见下图。

![结构设计图](/md/blog.004.jpeg "结构设计图")

图4.1 系统功能结构图
## 4.3数据库设计
开发一个系统软件还要提前设计方案数据库。这儿的数据库是统计数据的结合，存放在一起的数据信息都是按照一定的组织模式所进行的。现阶段，数据库能够立足于多种多样应用软件，这是因为其数据存储方式最好是，具备数据冗余率不高的优势。尽管数据库为应用程序给予信息存储服务，但它还能与程序流程维持相对较高的自觉性。总而言之，数据库经历了很长一段时间的高速发展，从最开始的不明，到现在的知名，其有关技术日趋成熟，但是也有扎实的理论基础。
### 4.3.1 数据库逻辑设计
（1）下图是酒店收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店收藏.jpg](/md/blog.005.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店收藏.jpg")
酒店收藏实体属性图

（2）下图是旅游景点收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点收藏.jpg](/md/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点收藏.jpg")
旅游景点收藏实体属性图

（3）下图是公告信息实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\公告信息.jpg](/md/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\公告信息.jpg")
公告信息实体属性图

（4）下图是字典表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\字典表.jpg](/md/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\字典表.jpg")
字典表实体属性图

（5）下图是游客实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\游客.jpg](/md/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\游客.jpg")
游客实体属性图

（6）下图是酒店留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店留言.jpg](/md/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店留言.jpg")
酒店留言实体属性图

（7）下图是酒店信息实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店信息.jpg](/md/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店信息.jpg")
酒店信息实体属性图

（8）下图是论坛实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\论坛.jpg](/md/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\论坛.jpg")
论坛实体属性图

（9）下图是旅游景点实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点.jpg](/md/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点.jpg")
旅游景点实体属性图

（10）下图是留言板实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\留言板.jpg](/md/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\留言板.jpg")
留言板实体属性图

（11）下图是旅游景点留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点留言.jpg](/md/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\旅游景点留言.jpg")
旅游景点留言实体属性图

（12）下图是导游实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\导游.jpg](/md/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\导游.jpg")
导游实体属性图

（13）下图是酒店预定实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店预定.jpg](/md/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\2\\_\_\_\_img\酒店预定.jpg")
酒店预定实体属性图

### 4.3.2 数据库物理设计
作为程序后台的支持，本数据库也需要设计数据存储的结构。而数据存储结构的设计就包括了数据表结构的设计和创建。数据表结构包括了字段，数据类型，还有字段的取值范围等信息。而E-R模型中的实体就是一张表，实体的特征就可以作为该表中的字段，根据本程序信息存储要求，设计每个字段需要的类型，还有该字段的取值范围等。每当设计完成一张数据表，就需要及时保存在数据库里面，并对该设计的数据表准确命名，要求设置的数据表的名称尽量不要是中文，而且要方便记忆。因为在程序编码阶段，通过SQL语句可以把程序里面的数据写入在各个数据表里面，而这个环节需要使用到数据表的名称。如果数据表名称是中文的话，可能会乱码并影响程序运行。下面就以表格形式展示设计的结果。

表4.1导游表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|daoyou\_name|String|导游姓名|是|
|3|daoyou\_photo|String|头像|是|
|4|daoyou\_phone|String|联系方式|是|
|5|daoyou\_email|String|邮箱|是|
|6|daoyou\_delete|Integer|假删|是|
|7|create\_time|Date|创建时间|是|
表4.2字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.3论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|游客|是|
|4|daoyou\_id|Integer|导游|是|
|5|users\_id|Integer|管理员|是|
|6|forum\_content|String|发布内容|是|
|7|super\_ids|Integer|父id|是|
|8|forum\_state\_types|Integer|帖子状态|是|
|9|insert\_time|Date|发帖时间|是|
|10|update\_time|Date|修改时间|是|
|11|create\_time|Date|创建时间|是|
表4.4旅游景点表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jingdian\_uuid\_number|String|景点编号|是|
|3|jingdian\_name|String|景点名称|是|
|4|jingdian\_types|Integer|景点类型|是|
|5|jingdian\_photo|String|景点图片|是|
|6|jingdian\_address|String|景点地址|是|
|7|jingdian\_money|BigDecimal|价格/人|是|
|8|jingdian\_clicknum|Integer|热度|是|
|9|zan\_number|Integer|赞|是|
|10|zai\_number|Integer|踩|是|
|11|jingdian\_text|String|日程路线|是|
|12|jingdian\_content|String|旅游景点详情|是|
|13|create\_time|Date|创建时间|是|
表4.5旅游景点收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jingdian\_id|Integer|旅游景点|是|
|3|yonghu\_id|Integer|游客|是|
|4|jingdian\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.6旅游景点留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jingdian\_id|Integer|旅游景点|是|
|3|yonghu\_id|Integer|游客|是|
|4|jingdian\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.7酒店信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jiudian\_name|String|酒店名称|是|
|3|jiudian\_types|Integer|房间类型|是|
|4|jiudian\_money|BigDecimal|价格/天|是|
|5|jiudian\_photo|String|酒店图片|是|
|6|jiudian\_address|String|酒店地址|是|
|7|jiudian\_clicknum|Integer|热度|是|
|8|zan\_number|Integer|赞|是|
|9|zai\_number|Integer|踩|是|
|10|shangxia\_types|Integer|冻结状态|是|
|11|jiudian\_content|String|酒店详情|是|
|12|create\_time|Date|创建时间|是|
表4.8酒店收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jiudian\_id|Integer|酒店|是|
|3|yonghu\_id|Integer|游客|是|
|4|jiudian\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.9酒店留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jiudian\_id|Integer|酒店|是|
|3|yonghu\_id|Integer|游客|是|
|4|jiudian\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.10酒店预定表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|游客|是|
|3|jiudian\_id|Integer|酒店|是|
|4|jiudian\_yuyue\_time|Date|预定时间|是|
|5|jiudian\_yuyue\_number|Integer|预定天数|是|
|6|create\_time|Date|创建时间|是|
表4.11留言板表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|游客|是|
|3|liuyan\_name|String|留言标题|是|
|4|liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|news\_name|String|公告标题|是|
|3|news\_types|Integer|景点信息|是|
|4|news\_photo|String|公告图片|是|
|5|insert\_time|Date|公告时间|是|
|6|news\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.13游客表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|游客姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|联系方式|是|
|5|yonghu\_email|String|邮箱|是|
|6|yonghu\_delete|Integer|假删|是|
|7|create\_time|Date|创建时间|是|
表4.14管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 第5章 系统实现
这个环节需要使用前面的设计方案，包括对系统模块的设计，还有对程序后台的数据支持的数据库的设计等。不过这部分内容还是强调系统编码人员的开发能力，要把前面设计的内容通过编码的形式以一个完整的，可以运行的系统呈现出来。

功能模块的实现
### 5.1游客信息管理
如图5.1显示的就是游客信息管理页面，此页面提供给管理员的功能有：游客信息的查询管理，可以删除游客信息、修改游客信息、新增游客信息，

还进行了对用户名称的模糊查询的条件

![](/md/blog.018.png)

图5.1 游客信息管理页面
### 5.2 酒店信息管理
如图5.2显示的就是酒店信息管理页面，此页面提供给管理员的功能有：查看已发布的酒店信息数据，修改酒店信息，酒店信息作废，即可删除，还进行了对酒店信息名称的模糊查询 酒店信息信息的类型查询等等一些条件。

![](/md/blog.019.png)


图5.2 酒店信息管理页面
### 5.3景点信息管理
如图5.3显示的就是景点信息管理页面，此页面提供给管理员的功能有：根据景点信息进行条件查询，还可以对景点信息进行新增、修改、查询操作等等。

![](/md/blog.020.png)



图5.3 景点信息管理页面
### 5.1公告信息管理
如图5.4显示的就是公告信息管理页面，此页面提供给管理员的功能有：根据公告信息进行新增、修改、查询操作等等。

![](/md/blog.021.png)

图5.4 公告信息管理页面





# 









