# Spring总结
1、Intellij IDEA创建Spring项目

    需要注意的一个地方：xml文件需要建立在src的直接路径下，不能是它的子文件夹下，因为这个问题，弄了一个小时才明白，所以刚开始学习，一定要多查网上的资料，
把步骤弄清楚。

该博主写的很详细，https://blog.csdn.net/chensanwa/article/details/79148929 （侵删）

http://how2j.cn/k/spring/spring-ioc-di/87.html 的总结：

Spring是一个基于IOC和AOP的结构J2EE系统的框架 

IOC 反转控制 是Spring的基础，Inversion Of Control 
简单说就是创建对象由以前的程序员自己new 构造方法来调用，变成了交由Spring创建对象 

DI 依赖注入 Dependency Inject. 简单地说就是拿到的对象的属性，已经被注入好相关值了，直接使用即可。 

传统的方式： 通过new 关键字主动创建一个对象

IOC方式

对象的生命周期由Spring来管理，直接从Spring那里去获取一个对象。 IOC是反转控制 (Inversion Of Control)的缩写，就像控制权从本来在自己手里，交给了Spring。 

打个比喻：
传统方式：相当于你自己去菜市场new 了一只鸡，不过是生鸡，要自己拔毛，去内脏，再上花椒，酱油，烤制，经过各种工序之后，才可以食用。
用 IOC：相当于去馆子(Spring)点了一只鸡，交到你手上的时候，已经五味俱全，你就只管吃就行了。
