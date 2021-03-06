# 设计模式的分类
1. 创建型模式
    - 工厂方法模式
    - 抽象工厂模式
    - 单例模式
    - 建造者模式
    - 原型模式
2. 结构型模式, 共七种
    - 适配器模式
    - 装饰器模式
    - 代理模式
    - 外观模式
    - 桥接模式
    - 组合模式
    - 享元模式
3. 行为型模式, 共十一种
    - 策略模式
    - 模板方法模式
    - 观察者模式
    - 迭代子模式
    - 责任链模式
    - 命令模式
    - 备忘录模式
    - 状态模式
    - 访问者模式
    - 中介者模式
    - 解释器莫忽视

# 设计模式的六大原则
## 开放封闭原则(Open Close Principle)
对扩展开放, 对修改封闭. 在程序需要进行拓展的时候, 不能去修改原有代码

## 里氏代换原则
任何基类可以出现的地方, 子类一定可以出现. LSP是继承复用的基石, 只有当衍生类可以替换掉基类, 软件单位的功能不受到影响时, 基类才能真正被复用. 里氏代换原则是对 "开-闭"原则的补充.

## 依赖倒置原则
这个是开闭原则的基础, 具体内容: 针对接口编程, 依赖于抽象而不依赖于具体.

## 接口隔离原则
使用多个隔离的接口, 比使用单个接口要好.  还是一个降低类之间的耦合度的意思.

## 迪米特法则(最少知道原则)
一个实体应当尽量少的与其他实体之间发生相互作用, 是的系统功能模块相对独立.

## 合成复用原则
尽量使用合成/聚合的方式, 而不是使用继承