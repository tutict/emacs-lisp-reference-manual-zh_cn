# Lisp数据类型
一个Lisp对象是由Lisp程序使用和操作的数据片段。对于我们的目的而言，类型或数据类型是一组可能的对象。  

每个对象至少属于一种类型。相同类型的对象具有相似的结构，通常可以在相同的上下文中使用。类型可以重叠，对象可以属于两个或更多类型。因此，我们可以询问一个对象是否属于某个特定类型，而不能询问对象的类型。  

Emacs内置了一些基本的对象类型。这些类型被称为原始类型，所有其他类型都是由它们构建的。每个对象都只属于一个原始类型。这些类型包括整数、浮点数、cons、符号、字符串、向量、哈希表、subr、字节码函数和记录，以及一些与编辑相关的特殊类型（如缓冲区）。（参见[Editing Types（编辑类型）]()。)  

每个原始类型都有一个对应的Lisp函数，用于检查对象是否属于该类型。  

在大多数编程语言中，程序员必须声明每个变量的数据类型，而类型则由编译器识别，但并不在数据中表示出来。Emacs Lisp中并不存在这样的类型声明。一个Lisp变量可以具有任何类型的值，并且它会记住您存储在其中的值，包括类型。（实际上，少量的Emacs Lisp变量只能取某种类型的值。参见[Variables with Restricted Values（具有受限值的变量）]()。）  

本章描述了GNU Emacs Lisp中每种标准类型的目的、打印表示和读取语法。关于如何使用这些类型的详细信息可以在后面的章节中找到。  
****************************************************************  
- [Printed Representation and Read Syntax（打印表示和读取语法）](./2.1-Printed_Representation_and_Read_Syntax（打印表示和读取语法）.md)  
- [Special Read Syntax（特殊读取语法）](./2.2-Special_Read_Syntax（特殊读取语法）.md)  
- [Comments（注释）](./2.3-Comments（注释）.md)  
- [Programming Types(编程类型)](./2.4-Programming_Types（编程类型）.md)  
- [Editing Types（编辑类型）](./2.5-Editing_Types（编辑类型）.md)  
- [Read Syntax for Circular Objects（循环对象的读取语法）](./2.6-Read_Syntax-for_Circular_Objects（循环对象的读取语法）.md)  
- [Type Predicates（类型谓词）](./2.7-Type_Predicates（类型谓词）.md)  
- [Equality Predicates（相等谓词）](./2.8-Equality_Predicates（相等谓词）.md)  
- [Mutability（可变性）](./2.9-Mutability（可变性）.md)  
*****************************************************************
下一章：[Numbers（数字）]()  
上一章：[Introduction（序言）](https://github.com/tutict/emacs-lisp-reference-manual-zh_cn/blob/main/%E7%BF%BB%E8%AF%91/%E7%AC%AC%E4%B8%80%E7%AB%A0Introduction/Introduction%EF%BC%88%E5%BA%8F%E8%A8%80%EF%BC%89.md)
