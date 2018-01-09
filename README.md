# swift-topics
##### 什么是 copy on write？

> 写时复制，指的是 swift 中的值类型，并不会在一开始赋值的时候就去复制，只有在需要修改的时候才去复制。
>
> [详细说明](https://www.jianshu.com/p/7e8ba0659646)

##### class 和 struct 的区别？

> class 为类，struct 为结构体，类是引用类型，结构体为值类型，结构体不可以继承。

##### Set 独有的方法有哪些？

> 1) union(_:): Set 取并集
>
> 2) intersection(_:): Set 取交集
>
> 3) symmetricDifference(_:): Set 取差集
>
> 4) subtracting(_:): Set 取对称差集