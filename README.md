# 模板字符串
用反引号（`）标识。它可以当作普通字符串使用，也可以用来定义多行字符串，或者在字符串中嵌入变量。 

模板字符串的空行和换行，都是被保留的。可以用trim方法消除它。  
模板字符串中嵌入变量，需要将变量名写在${}之中。

```
${x} + ${y} = ${x + y}
```
如果大括号内部是一个字符串，将会原样输出。
# 标签模板
模板字符串可以紧跟在一个函数名后面，函数将被调用来处理这个模板字符串。这被称为“标签模板”功能（tagged template）。
