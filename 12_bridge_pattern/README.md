# 桥接模式（Bridge Pattern）

将抽象部分与它的实现部分分离，使它们都可以独立地变化。

> 在这个例子中，抽象部分为颜色，实现部分为形状
> 与策略模式类似，但不同在于策略模式没有对实现进行抽象，只对策略进行抽象

# 动机

实体的变化维度有多个，并且这些维度也需要独立扩展，且实现部分也可抽象，就可以使用桥接模式来减少代码量，增强扩展性。
