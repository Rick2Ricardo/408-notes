实验报告书上也有题目

# 操作系统

## 第一章

### 操作系统的目标和作用

目标：方便性、有效性、可扩充性、开放性

作用：

+ 作为用户与计算机硬件系统之间的接口
+ 作为计算机系统资源的管理者
+ 实现了对计算机资源的抽象

实时操作系统中并不是所有的任务一定要在截至时间完成（软实时任务）

### 操作系统的基本特性

并发：

共享：

虚拟：

异步：

### 操作系统的主要功能

#### 处理机管理功能

#### 存储器管理功能

#### 设备管理功能

#### 文件管理功能

#### 操作系统与用户之间的接口

### 微内核OS结构

微内核操作系统的优点

微内核操作系统存在的问题

### 课后习题

2 9 11 15 16 17 18 20 21

## 第二章

### 2.2 进程的描述

#### 2.2.2进程的基本状态及转换

##### 1.进程的三种基本状态

##### 2.三种基本状态的转换

##### 3.创建状态和种植状态

### 2.4进程同步



三个机制

着重看读者写者问题：关注为什么要readcount 来记录读者的数量，注意readcount的使用方法

注意函数和信号量一定要声明

2.5.3第二个读者写者2问题领会设置一个上限的时候怎么处理RN

重点搞懂读者写者问题

还有独木桥问题（再加一个最多有n个人，这个要怎么解决，只用PV操作，不用信号量）要写注释，让老师看得懂

管道通信，是什么，特点是什么，五个特点记住

## 第三章 处理机调度与死锁

作业的三个基本状态

银行家算法（图要看，过程写清楚）

容易忽略的步骤：

+ 判断不能少，少了就扣分
+ 前面三步不能少，少了就没分

## 第四章 存储器管理

程序的装入和连接！！！

分别发生在什么契机

课后题做一下

连续分配存储的算法，优缺点

索引

对换：是以进程为单位的
置换：是以页/段作为对换的单位

快表的作用

习题

3 4  5 14 17 

21 22 24

## 第五章（出的题目还是蛮多的）

5.2请求页表机制 长条全部背下来

5.3请求分段中的长条，全部背下来

5.3最佳置换算法的几个算法（要记住简写对应的算法，不要搞错了）一五一十掌握 要把图给画出来，如同书上的例子一样，一条一条的

缺页率9+3/20（把前三个当作缺页，或者把前面三个不算缺页都写以下，讨论）

预调页LRU LFU

Clock置换算法，*作为访问的标志

clock算法的计算题

缺页中断

## 实验指导书

### 实验三

输出是什么样的，创建子进程第三题

画个进程树出来

系统调用有哪些

看一下第66页的函数

ls

第一个实验的表格，看看目录操作的表格（第五页）(第六页)