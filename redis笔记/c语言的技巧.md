# C语言的技巧
> 记录一下C语言的编程技巧（潜规则）。

## 1.函数宏中的多行处理
源码中有很多函数宏，其中都是do{ ... } while(0)的结构。其理由为编译器展开宏的时候，能够正确处理多行函数。

参考文章：https://www.cnblogs.com/lanxuezaipiao/p/3535626.html