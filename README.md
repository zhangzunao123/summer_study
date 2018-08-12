# summer_study

## day_1
- git process
i- web
## day_2
- linux一些常用指令
```
cd ..
ls
cat
vim
pwd
rm -rf
cp
mv

```

- Git

```
git status
git diff  //查看改动
git add .
git commit -m ""
git push origin master
git checkout -f    //强制恢复

```

- vim

```
i  //插入
esc  //返回命令状态
:wq  //保存并推出
:q!  //强制退出
:$  //跳到最后一行
/  //查找
```
- 学习python tornado制作一个网页的基础框架
## day_3
- 学习Vscode java 的入门教程 但是刚接触什么都不会在百度无限制搜索
最后找到Holle Word！的基础教学
  www.jb51.net
## day_4
- 学习Java的数据结构
- 枚举
   创建枚举类型要使用 enum 关键字，隐含了所创建的类型都是 java.lang.Enum 类的子类（java.lang.Enum 是一个抽象类）。枚举类型符合通用模式 Class Enum<E extends Enum<E>>，而 E 表示枚举类型的名称。枚举类型的每一个值都将映射到 protected Enum(String name, int ordinal) 构造函数中，在这里，每个值的名称都被转换成一个字符串，并且序数设置表示了此设置被创建的顺序
int compareTo(E o)            比较此枚举与指定对象的顺序
Class<E> getDeclaringClass()  返回与此枚举常量的枚举类型相对应的 Class 对象
- 位集合
Bitset容器是用来存放bit位元素的，每个元素只占1bit位，取值为0或者1，因而比较节约存储空间，bitset提供了多种方法操作位容器，使用前添加<bitset>头文件即可使用
- 向量
Vector和数组非常类似，但是它可以存储多个对象，并且可以根据索引值来检索这些对象。数组和Vector的最大区别就是当空间用完以后，Vector会自动增长。同时Vector还提供了额外的方法来增加或者删除元素，而在数组中，必须手工完成
- 栈
栈是计算机中经典的数据结构，简单的说，栈就是限制在一端进行插入删除操作的线性表。栈有两种最重要的操作，即pop（从栈顶弹出一个元素）和push（将一个元素进栈）
- 字典
- 哈希表
数组和向量都可以存储对象，但对象的存储位置是随机的，也就是说对象本身与其存储位置之间没有必然的联系。当要查找一个对象时，只能以某种顺序（如顺序查找或二分查找）与各个元素进行比较，当数组或向量中的元素数量很多时，查找的效率会明显的降低。

一种有效的存储方式，是不与其他元素进行比较，一次存取便能得到所需要的记录。这就需要在对象的存储位置和对象的关键属性（设为 k）之间建立一个特定的对应关系（设为 f），使每个对象与一个唯一的存储位置相对应。在查找时，只要根据待查对象的关键属性 k 计算f(k)的值即可。如果此对象在集合中，则必定在存储位置 f(k)上，因此不需要与集合中的其他元素进行比较。称这种对应关系 f 为哈希（hash）方法，按照这种思想建立的表为哈希表
- 哈希算法，是一类算法
- 哈希表（Hash） 是一种数据结构
- 哈希函数，是支撑哈希表的一类函数；
- Map 是映射 地图的意思，在java中Map表示一种把K映射到V的数据类型；
- HashMap 是java中用哈希数据结构实现的Map；



- 属性
- RUNOOB.com

## python  基础命令
python print2 不需要括号
python printt3 需要括号
代码块区分：以冒号‘：’结尾
注意 input（）返回类型是str，要使用时注意转换类型 不然会报错

python 解释性语言
优点；简单 功能强大 支持面向对象
特点；大小写严格区分  简单易学 支持面向对象  开源（python中的程序源代码是可以看得到的，可以>复制）  库（标准库）非常丰富    跨平台使用  解释性语言  高级语
## 变量赋值
- 每个变量在使用前都必须赋值，变量赋值以后该变量才会被创建
- 用等号（=）来给变量赋值
- 等号左边是变量名  右边是存储在变量中的值
```
counter = 100 #赋值整形变量
miles = 1000.0 #浮点型
name = "John" #字符串
```
Python支持四种不同的数字类型：

int（有符号整型）
long（长整型[也可以代表八进制和十六进制]）
float（浮点型）
complex（复数）


- 字符串或串(String)是由数字、字母、下划线组成的一串字符。

一般记为 :

s="a1a2···an"(n>=0)
它是编程语言中表示文本的数据类型。

python的字串列表有2种取值顺序:

从左到右索引默认0开始的，最大范围是字符串长度少1
从右到左索引默认-1开始的，最大范围是字符串开头


python中把数字分成两种数字 int类和float类  浮点运算
在python中输入较大的数字会自动转化为长整数


- 学会用#来注释

- 学会将字符串储存到变量中

- 学会使用for循环，和print打印结果


问题
计算胰岛素序列中的氨基酸频率

```
# insulin [Homo sapiens] GI:386828
insulin = "MALWMRLLPLLALLALWGPDPAAAFVNQHLCGSHLVEALYLVCGERGFFYTPKTRREAEDLQVGQVELGGGPGAGSLQPLALEGSLQKRGIVEQCCTSICSLYQLENYCN"for aa in "ACDEFGHIKLMNPQRSTVWY":
number = insulin.count(aa)
print(aa, number)
```
# 开头的是注释

第二行insulin = "MAL..."则将蛋白质序列储存在名为insulin的变量中；

for aa in "ACD...":表示遍历二十个氨基酸的循环，需要注意的是for语句末尾的冒号告诉Python，下一行是循环的第一行，而且在Python中用缩进（注意！是四个空格，若是使用编辑器比如Atom，则把Tab Length改成4）来判断代码之间的关系，在前面的示例中，因为后面两行的缩进，所以表示了这两行包括在for循环中；当for循环使用的序列是字符串时，循环内的代码会一个个遍历整个字符串；

number = insulin.count(aa)这一行使用count计算一个字符在一段文本中出现个数；

print(aa, number)将氨基酸和个数打印出来，在Python3中使用的是print函数。


在Python字符串中需要有单引号'abc'、双引号"abc"或三引号'''abc'''，"""abc"""进行封闭。

单引号和双引号都可以用来表示一个字符串


##定义一个函数
简单的规则；
- 函数代码块以 def 关键词开头，后面跟着函数标识符名称和圆括号()。
- 任何传入参数和自变量必须放在圆括号中间。圆括号之间可以用来定义参数。
- 函数的第一行语句可以选择性地使用文档字符串—用于存放函数说明。
- 函数内容以冒号起始，并且缩进。
- return [表达式] 结束函数，选择性地返回一个值给调用方。不带表达式的return相当于返回 None。

## python 的缺点 
- 1.运行速度慢相比C程序非常慢，因为python是一种解释性的语言代码在执行时会翻译成CPU能理解的机械码，这个翻译过程非常消耗时间
- 2.代码不能加密发布python就相当于发布你的源代码解释性的语言发布都是相当于发布源代码


# 学习
在python交互模式下，可以直接输入代码，然后执行，并立刻得到结果。
在命令行模式下，可以直接运行.py文件
用文本编译器写python城西，然后保存为.py的文件，就可以用python直接运行这个程序了。
直接输入python进入交互模式，相当于启动了Python解释器，但是等待你一行一行地输入源代码，每输入一行就执行一行。

直接运行.py文件相当于启动了Python解释器，然后一次性把.py文件的源代码给执行了，你是没有机会以交互的方式输入源代码的。
用Python开发程序，完全可以一边在文本编辑器里写代码，一边开一个交互式命令窗口，在写代码的过程中，把部分代码粘到命令行去验证

