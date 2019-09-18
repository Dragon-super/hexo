> Ioc是一种设计思想,称之为控制反转.基于这种思想实现对象创建,对象的科学管理以及应用时的解耦(借助Di机制实现).Sping框架核心就是基于这种机制进行了完美实现

说明：
    控制反转讨论的是什么？谁控制谁的问题
    生活中Ioc的实现？
***
##### Spring Bean容器的初始化
1. 如何理解Sping中的Bean对象?
 > 由Spring管理的对象都是Bean对象
    
2. 如何理解Sping中的Bean容器?
 > 存储Bean对象的容器,可以是Map对象  
    
3. 我们自己写的类如何交给Spring管理
 > 1. 通过Xml文件描述,    例如 `<Bean Id="" Class="">`
 > 2. 通过注解方式进行描述,例如@Controller,@Service

4. Sping中Bean对象的类型
 > 1. 未实现Beanfactory接口的对象
 > 2. 未实现Beanfactory接口的对象
    
5. Sping中如何创建Bean对象?
 > 1. 借助工厂(Beanfactory)基于反射技术创建Bean对象

6. Spring管理的Bean对象常用作用域
 > 
    
7. Spring管理的Bean对象是否支持延时加载?支持

8. 如何自己设计一个Ioc容器呢?
 > 例如Spring中的Bean对象容器初始化   
*** 
##### Spring
1. 如何理解Spring中的两大map对象
