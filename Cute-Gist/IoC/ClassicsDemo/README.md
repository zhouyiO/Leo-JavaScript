> 学习资料：
> 1. [《了不起的 IoC 与 DI》](https://juejin.im/post/6861749411362373639)
> 1. [《依赖注入》](https://www.yuque.com/midwayjs/midway_v2/container)

`@Provide` 的作用是告诉 依赖注入容器，我需要被容器所加载。 
`@Inject` 装饰器告诉容器，我需要将某个实例注入到属性上。

通过这两个装饰器的搭配，我们可以方便的在任意类中拿到实例对象，就像上面的 this.userService 。