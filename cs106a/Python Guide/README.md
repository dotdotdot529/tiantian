Python Guide
[From stanford](https://cs.stanford.edu/people/nick/py/)
---

# About Python
## Open Source
> 顾名思义-开放源代码，这使得所有感兴趣的人都可以阅读，学习，甚至进行自己的contribution，很多project都是因为开源而大放异彩，因为更多的人融入，越来越多人使用，也越来越多人一起优化迭代

## Cross Platform
> 跨平台：简而言之就是你写的Python代码能在Windows/Apple/Linux多个平台去运行，i.e. one piece of code runs every where
> 如果没有跨平台能力意味着什么：你将失去所有不能跑你代码的平台用户，当然你会说我不会放弃他们的，我为他们在单独写一个能在这些平台跑的代码，那么你的代码维护性就非常重了，因为你要有好几份代码


# Python Interpreter
> 还记得你在setup section中安装并运行python命令吗？这个python命令就是解释器，你写的代码他来逐行读取，并将它解释为计算机可以理解的语言，进而完成你所编写的逻辑

```bash
# 看看下面字符串拼接的小例子

# Step1: Open your terminal

# Step2: 输入python指令
>>> python

# Step3: 完成一个字符串拼接的小任务，输入以下指令 + Enter
# 你会看到输出的结果：'hello!'
# !!! What you learn from here is that the plus sign(+) can be used to concatenate strings 
# 你可以自己敲击其他字符试试，比如: 'family' + 'who' + 'knows'
>>> 'hello' + '!'

# 再来看看这个
>>> 'hello' + 2
TypeError: can only concatenate str (not "int") to str
# 看看上个例子关于+的说明，你就明白了
```

```python
# Do some math

# you can use it as a calculator
>>> 1 + 2 * 3

# max是python内置的一个函数，可以供你使用
>>> max(1, 5, -2)

>>> 'hello' + 2
```

- 你一定想问如果你想退出python怎么办？
```bash
Enter Ctrl+D to abort the process
```