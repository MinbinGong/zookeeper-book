拥有Zookeeper使得一整个新类别的应用得以被开发？似乎并不是这样。Zookeeper简化了开发的进程，是的开发更加的敏捷，同时又能提供更加鲁棒性的实现。

以前系统也实现过像分布式锁管理者这样的组件或者使用分布式数据库用户协同服务。实际上，Zookeeper借用了很多来自以前系统的概念。然而，它不会暴露出一个锁服务的接口或者一个存储数据的通用接口。Zookeeper被设计成是专有的并且非常关注与协同任务。同时，它不会试着强加一组特定同步原语给开发者，这样使得能够实现的东西更加的灵活。

当然，没有Zookeeper也能构建分布式系统。然而，Zookeeper提供给开发者专注于应用逻辑而不是难懂的分布式系统概念的机会。没有Zookeeper进行分布式系统编程是可行的，但是会更加困难。

