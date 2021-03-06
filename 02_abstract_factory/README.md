# 抽象工厂（Abstract Factory）

抽象工厂模式定义了一个产生一组抽象产品的抽象工厂，由具体的工厂决定实例化的产品是哪一组。

> 工厂依赖于抽象产品族，具体产品族依赖于抽象产品族，体现了依赖倒置原则
>
> 每有一个新的产品族，只需要再新增一个具体工厂即可，体现了开闭原则

# 动机

当系统中的工厂可能会引进多种产品族的时候，可使用此模式。

> 对于某个产品族本身进行扩展，会破坏开闭原则
