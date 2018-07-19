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

