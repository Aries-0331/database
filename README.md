# Database
[《Let's Build a Simple Database》](https://cstack.github.io/db_tutorial/)

## Some tips
- what is REPL?
  - A read–eval–print loop (REPL), also termed an interactive toplevel or language shell, is a simple interactive computer programming environment that takes single user inputs, executes them, and returns the result to the user; a program written in a REPL environment is executed piecewise.
  
- differences between `size_t` and `ssize_t`
  - `ssize_t` is the same as `size_t`, but is a signed type - read ssize_t as “signed `size_t`”. `ssize_t` is able to represent the number -1, which is returned by several system calls and library functions as a way to indicate error.

- makefile
  - $@ -- 表示目标文件
  - $^ -- 表示所有依赖文件
  - $< -- 表示第一个依赖文件
  - $? -- 表示比目标还要新的依赖文件列表
  - ?= -- 如果没有被赋值过，就赋予等号后面的值
