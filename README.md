# KotlinProject
kotlin声明函数
```
/**
 * 函数声明 可以定义在类外面
 * fun 为关键字
 * 形参  参数名：参数类型
 * fun + 函数名称（形参）：返回值类型{
 *     函数体
 * }
 */
fun main(args : Array<String>){
    println("hello world!")

    println(max(1,2))

    println(min(3,4))
}

//代码块函数体
fun max(a:Int,b:Int): Int {
    return if (a>b) a else b
}

//表达式函数体 可以不加返回值类型
fun min(a:Int,b:Int) = if (a>b) b else a

//if是表达式，在java中 if是语句
//语句和表达式的区别：表达式有值，并且能作为另一个表达式的一部分使用。
//语句没有自己的值，里面包含着它的代码块中顶层元素
```
