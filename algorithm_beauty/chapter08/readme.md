# 栈

如何实现浏览器的前进后退？

栈：后进者先出，先进者后出。

从特性上看，栈是一种操作受限的线性表，只允许一端进行插入和删除数据。

实际上，栈可以用数组实现，也可以用链表实现。区别就是顺序栈和链式栈。

- 栈在函数调用中的应用

操作系统给每个线程分配一块独立的内存，这块内存会被组织成栈的结构，用来存储函数调用时的临时变量。

- 栈在表达式求值中的应用
- 栈在括号匹配中的应用