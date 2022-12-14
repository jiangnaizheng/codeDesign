# java 设计模式

## 设计原则

1. 单一职责原则
    一个类只负责一个功能领域中的相应职责。即对一个类而言， 应该只有一个引起它变化的原因。
2. 开闭原则
   一个软件实体应当对扩展开放，对修改关闭。即软件实体应尽量在不修改原有代码的情况下进行扩展。为了满足开闭原则，需要对系统进行抽象化设计（面向抽象层）
3. 里式替换原则
   所有引用基类（父类）的地方必须能透明地使用其子类的对象。在程序中尽量使用基类来对对象进行定义，在运行时再确定其子类类型，用子类对象来替换父类
4. 依赖倒转原则
   抽象不应该依赖于细节，细节应该依赖于抽象。即要针对接口编程，而不是针对实现编程。要求在程序中尽量引用层次高的抽象层类，将具体类的对象通过依赖注入的方式注入其他对象中。依赖注入包括**构造注入**、**设值注入（Setter注入）**和**接口注入**。
5. 接口隔离原则
   使用多个专门的接口，而不使用单一的总接口，即客户端不应该依赖那些它不需要的接口。
6. 合成复用原则
   尽量使用对象组合，而不是继承来达到复用的目的。**复用时要尽量使用组合/聚合关系，少用继承**。
7. 迪米特原则
   一个软件实体应当尽可能少地于其他实体发生相互作用。

## 设计模式

### 创建型模式

1. 单例模式
2. 简单工厂模式
3. 工厂方法模式
4. 抽象工厂模式
5. 原型模式
6. 建造者模式

### 结构型模式

1. 适配器模式
2. 桥接模式
3. 组合模式
4. 装饰模式
5. 外观模式
6. 享元模式
7. 代理模式

### 行为型模式

1. 职责链模式
2. 命令模式
3. 解释器模式
4. 迭代器模式
5. 中介者模式
6. 备忘录模式
7. 观察者模式
8. 状态模式
9. 策略模式
10. 模板方法模式
11. 访问者模式
