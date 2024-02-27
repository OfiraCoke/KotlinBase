# 我的第一个 Kotlin 程序

Kotlin 程序文件以 .kt 结尾，如：hello.kt 、app.kt。

```
package hello                      //  可选的包头
 
fun main(args: Array<String>) {    // 包级可见的函数，接受一个字符串数组作为参数
   println("Hello World!")         // 分号可以省略
}
```

```
class Greeter(val name: String) {
   fun greet() { 
      println("Hello, $name")
   }
}
 
fun main(args: Array<String>) {
   Greeter("World!").greet()          // 创建一个对象不用 new 关键字
}
```

# 为什么选择 Kotlin？

简洁: 大大减少样板代码的数量。
安全: 避免空指针异常等整个类的错误。
互操作性: 充分利用 JVM、Android 和浏览器的现有库。
工具友好: 可用任何 Java IDE 或者使用命令行构建。
