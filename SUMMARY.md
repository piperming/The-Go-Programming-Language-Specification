* [简介-Introduction](01/00.md)
* [符号-Notation](02/00.md)
* [源码表示-Source code representation](03/00.md)
    * [字符-Characters](03/01.md)
    * [字母和数字-Letters and digits](03/02.md)
* [词法元素-Lexical elements](04/01.md)
    * [注释-Comments](04/01.md)
    * [令牌-Tokens](04/02.md)
    * [分号-Semicolons](04/03.md)
    * [标识符-Identifiers](04/04.md)
    * [关键字-Keywords](04/05.md)
    * [操作符和定界符-Operators and Delimiters](04/06.md)
    * [整型字面量-Integer literals](04/07.md)
    * [浮点型字面量-Floating-point literals](04/08.md)
    * [复数字面量-Imaginary literals](04/09.md)
    * [Rune literals](04/10.md)
    * [字符型字面量-String literals](04/11.md)
* [常量-Constants](05/00.md)
* [变量-Variables](06/00.md)
    * [Type-Types](06/01.md)
    * [方法组合-Method sets](06/02.md)
    * [布尔型-Boolean types](06/03.md)
    * [数字型-Numeric types](06/04.md)
    * [字符型-String types](06/05.md)
    * [数组-Array types](06/06.md)
    * [切片-Slice types](06/07.md)
    * [结构体-Struct types](06/08.md)
    * [指针-Pointer types](06/09.md)
    * [函数-Function types](06/10.md)
    * [接口-Interface types](06/11.md)
    * [字典-Map types](06/12.md)
    * [Channel-Channel types](06/13.md)
    * [Type属性、值-Properties of types and values](06/14.md)
    * [Type的表示-Type identity](06/15.md)
    * [可换让性-Assignability](06/16.md)
* [块-Blocks](07/00.md)
* [声明范围-Declarations and scope](08/00.md)
    * [标签范围-Label scopes](08/01.md)
    * [空白符-Blank identifier](08/02.md)
    * [预声明标识符-Predeclared identifiers](08/03.md)
    * [输出标识符-Exported identifiers](08/04.md)
    * [Uniqueness of identifiers](08/05.md)
    * [常量声明-Constant declarations](08/06.md)
    * [Iota-Iota](08/07.md)
    * [Type声明-Type declarations](08/08.md)
    * [变量声明-Variable declarations](08/09.md)
    * [变量声明简写-Short variable declarations](08/10.md)
    * [函数声明-Function declarations](08/11.md)
    * [方法声明-Method declarations](08/12.md)
* [表达式-Expressions](09/00.md)
    * [操作数-Operands](09/01.md)
    * [Qualified identifiers](09/02.md)
    * [复数字面量-Composite literals](09/03.md)
    * [函数字面量Function literals](09/04.md)
    * [基本表达式-Primary expressions](09/05.md)
    * [Selectors-Selectors](09/06.md)
    * [方法表示方式-Method expressions](09/07.md)
    * [方法的值-Method values](09/08.md)
    * [下标表示方式-Index expressions](09/09.md)
    * [切片表示方式-Slice expressions](09/10.md)
    * [type断言-Type assertions](09/11.md)
    * [调用-Calls](09/12.md)
    * [传递不定参数-Passing arguments to ... parameters](09/13.md)
    * [一元运算符-Operators](09/14.md)
    * [算术运算符-Arithmetic operators](09/15.md)
    * [比较运算符-Comparison operators](09/16.md)
    * [逻辑运算符-Logical operators](09/17.md)
    * [地址运算符-Address operators](09/18.md)
    * [Receive运算符-Receive operator](09/19.md)
    * [转换-Conversions](09/20.md)
    * [常量运算符-Constant expressions](09/21.md)
    * [Order of evaluation](09/22.md)
* [语句-Statements](10/00.md)
    * [结束语句-Terminating statements](10/01.md)
    * [空语句-Empty statements](10/02.md)
    * [Labeled statements](10/03.md)
    * [表达式声明-Expression statements](10/04.md)
    * [Send statements](10/05.md)
    * [自增自减语句-IncDec statements](10/06.md)
    * [Assignments](10/07.md)
    * [if条件语句声明-If statements](10/08.md)
    * [switch语句声明-Switch statements](10/09.md)
    * [for语句声明-For statements](10/10.md)
    * [go语句声明-Go statements](10/11.md)
    * [select语句声明-Select statements](10/12.md)
    * [return语句声明-Return statements](10/13.md)
    * [break语句声明-Break statements](10/14.md)
    * [contine语句声明-Continue statements](10/15.md)
    * [goto语句声明-Goto statements](10/16.md)
    * [falthrough语句声明-Fallthrough statements](10/17.md)
    * [defer语句声明-Defer statements](10/18.md)
* [Built-in functions](11/00.md)
    * [Close](11/01.md)
    * [长度、空间-Length and capacity](11/02.md)
    * [分配-Allocation](11/03.md)
    * [创建slice、map、channel-Making slices, maps and channels](11/04.md)
    * [切片追加、拷贝-Appending to and copying slices](11/05.md)
    * [删除map元素-Deletion of map elements](11/06.md)
    * [操纵复数-Manipulating complex numbers](11/07.md)
    * [处理panic-Handling panics](11/08.md)
    * [Bootstrapping](11/09.md)
* [包-Packages](12/00.md)
    * [源码结构-Source file organization](12/01.md)
    * [Package-clause](12/02.md)
    * [Import声明-Import declarations](12/03.md)
    * [package示例-An example package](12/04.md)
* [程序的初始化和执行-Program initialization and execution](13/00.md)
    * ["零"值-The zero value](13/01.md)
    * [package初始化-Package initialization](13/02.md)
    * [执行程序-Program execution](13/03.md)
* [Error类型-Errors](14/00.md)
* [Run-time panics](15/00.md)
* [系统注意事项-System considerations](16/00.md)
    * [不安全的包-Package unsafe](16/01.md)
    * [Size and alignment guarantees](16/02.md)
