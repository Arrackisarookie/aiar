---
title: "PEP 翻译计划"
date: 2021-05-26T08:37:36+08:00
draft: true
categories:
    - 技术
tags:
    - plan
    - PEP
    - Python
---

> 原文标题：Python PEP—Python增强提案  
> 原文作者：hiyo  
> 原文链接：[https://blog.csdn.net/u010698107/article/details/112756105](https://blog.csdn.net/u010698107/article/details/112756105)

PEP的全称是Python Enhancement Proposals，Python增强提案。描述了Python的语言特性、功能、编程规范等，包括了技术规范和功能的基本原理说明，是了解Python语言的详细指南。PEP创建于2000年，到目前已经有上千个提案了，下面介绍几个值得仔细阅读了解的提案。

PEP官网：https://www.python.org/dev/peps/

## PEP 8 - 编码规范
PEP 8 – Style Guide for Python Code：定义了编写 Python 代码的规范和编码原则

## PEP 257 - 文档注释
PEP 257 – Docstring Conventions
文档注释规范

## PEP 20 - Python之禅
PEP 20 – The Zen of Python
Python之禅，在Python终端导入this模块查看：

``` python
import this
```

```
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

## PEP 202 - 列表
PEP 202 – List Comprehensions
列表生成式

## PEP 274 - 字典
PEP 274 – Dict Comprehensions
字典生成式

## PEP 234 - 迭代器
PEP 234 – Iterators
迭代器

## PEP 279 - enumerate
PEP 279 – The enumerate() built-in function
enumerate枚举函数

## PEP 282 - 日志
PEP 282 – A Logging System
日志模块

## PEP 289 - 生成器
PEP 289 – Generator Expressions
生成器表达式

## PEP 318 - 装饰器
PEP 318 – Decorators for Functions and Methods
装饰器

## PEP 309 - 偏函数
PEP 309 – Partial Function Application：Python 偏函数

## PEP 333 - web 服务
PEP 333 – Python Web Server Gateway Interface v1.0：Web开发相关，WSGI协议，描述 web 服务器和 Python web 应用程序\框架之间的标准接口。
PEP 3333 – Python Web Server Gateway Interface v1.0.1：PEP 333的更新版本

## PEP 343 - with语句
PEP 343 – The “with” Statement
with语句

## PEP 484 - 类型提示
PEP 484 – Type Hints：Python类型提示（Type Hints），在Python3.5.0中引入，允许开发者指定变量类型。

## PEP 342 - 协程
PEP 342 – Coroutines via Enhanced Generators：协程和yield

## PEP 498 - 字符串插值
PEP 498 – Literal String Interpolation
Python3.6新提出的字符串插值方法：
``` shell
>>> import datetime
>>> name = 'Fred'
>>> age = 50
>>> anniversary = datetime.date(1991, 10, 12)
>>> f'My name is {name}, my age next year is {age+1}, my anniversary is {anniversary:%A, %B %d, %Y}.'
'My name is Fred, my age next year is 51, my anniversary is Saturday, October 12, 1991.'
>>> f'He said his name is {name!r}.'
"He said his name is 'Fred'."
```

## PEP 3101 - 字符串格式化
PEP 3101 – Advanced String Formatting
字符串格式化
