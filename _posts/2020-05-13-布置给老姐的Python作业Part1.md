---
layout: post
title: "布置给老姐的Python作业Part1"
subtitle: 'IO读写'
author: "Bk96"
header-style: text
tags:
  - Python
---

一门编程语言的学习总是离不开IO(*Input & Output*)


### 情景一

假设你作为一个老师，一个同学第一次遇到你会和你打招呼，你需要作出相应的回应。

***英文名由lastname和firstname构成，并以:分割,学生的问候总是以Hello, I'm fn:ln的形式。你需要输出hello, ln***.

下面是一个输入输出的例子.

```python
Input:
Hello,I'm michael:jackson.
Output:
Hello michael.
```

#### 关键要素:

`raw_input();str.split();print()`

### 情景二

一次考试结束了，你作为老师需要奖励班级前三名的同学。

下面是一个输入输出的例子.

```python
Input:
5
Tom:Johnson 80
michael:jackson 100
Ben:Simon  85
James:Hardon 90
Kobe:Bryant 95
Output:
michael James Kobe
```

#### 关键要素:

`list数据结构;sort();Python分片`


### 情景三

作为情景二的升级版本，你作为一个老师，拿到的是一个成绩单（假设情景二的输入都保存在文件中），你需要写一份奖状（将情景二的Output输出到文件中)，假设输入输出文件分别是*grade.txt*和*jiangzhuang.txt*

#### 关键要素:

`open();cloase();read();readlines();`





*Enjoy it.*

