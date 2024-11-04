●实验目的

通过UML建模过程掌握类的分析与设计方法。

●实验环境

StarUML

●实验任务

针对“迷你图书管理系统”的用例图，开展分析，完成类建模。
●实验步骤

分析实验任务内容，并利用UML完成类的建模并生成对象，主要包括：

1.定义类（包括类名、属性、操作等）

2.建模类之间的关系（包含关联、泛化、依赖、实现等）

3.构建完整的类图（至少包含抽象类、组合、聚合、多重性、可见性和接口等）

4.根据类图，生成系统某一时刻的对象图

注意：上述括号中的内容必须体现在图中，缺一项本实验得分扣5分；请自行设计类图和对象图，注意逻辑。

●实验过程
![image]

1.完整的类图：
分析：

上图总的来说共有六个类，其中分别是User,RegisteredUser,OrdinaryUser,LibraryManager,MailSystem,Library.

其中，MailSystem是接口。User类关联RegisterUser和OrdinaryReader类，同时这两个类和User之间也存在聚集关系，LibraryManager和 OrdinaryReader都继承RegisterUser类。Library

类依赖于RegisterUser和 OrdinaryReader类；LibraryManager还实现了MailSystem接口,又

和Library之间存在组成关系，各个类都设置了一定的可见性，有的定义了一些操作方法。

2.对象图：

从上图可以看出有三个对象。
