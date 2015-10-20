# CompositePattern

> 组合设计模式的完整实现

![demo.png](http://images2015.cnblogs.com/blog/607542/201510/607542-20151017215057132-320922577.png)

* 命令对象封装了如何对目标执行指令的信息，因此客户端或调用者不必了解目标的任何细节，却仍可以对他执行任何已有的操作。通过把请求封装成对象，客户端可以把它参数化并置入队列或日志中，也能够支持可撤销操作。命令对象将一个或多个动作绑定到特定的接收器。命令模式消除了作为对象的动作和执行它的接收器之间的绑定。
