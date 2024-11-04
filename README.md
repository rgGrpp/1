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
![圖片](https://github.dev/rgGrpp/1/blob/main/%E8%BF%B7%E4%BD%A0%E5%9C%96%E6%9B%B8%E9%A4%A8%E8%A3%A1%E7%B3%BB%E7%B5%B1%E7%94%A8%E4%BE%8B%E5%9C%96)

1.完整的类图：
分析：
![圖片](https://github.com/rgGrpp/1/blob/main/%E5%AE%8C%E6%95%B4%E7%9A%84%E9%A1%9E%E5%9C%96.png)
上图总的来说共有六个类，其中分别是User,RegisteredUser,OrdinaryUser,LibraryManager,MailSystem,Library.

其中，MailSystem是接口。User类关联RegisterUser和OrdinaryReader类，同时这两个类和User之间也存在聚集关系，LibraryManager和 OrdinaryReader都继承RegisterUser类。Library

类依赖于RegisterUser和 OrdinaryReader类；LibraryManager还实现了MailSystem接口,又

和Library之间存在组成关系，各个类都设置了一定的可见性，有的定义了一些操作方法。

2.对象图：
![圖片](https://github.dev/rgGrpp/1/blob/main/%E8%BF%B7%E4%BD%A0%E5%9C%96%E6%9B%B8%E9%A4%A8%E8%A3%A1%E7%B3%BB%E7%B5%B1%E7%94%A8%E4%BE%8B%E5%9C%96)
从上图可以看出有三个对象。
