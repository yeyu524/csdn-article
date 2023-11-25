> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/qq_46207024/article/details/121483848?spm=1001.2014.3001.5502)

目录
--

0：Base [API](https://so.csdn.net/so/search?q=API&spm=1001.2101.3001.7020)
-------------------------------------------------------------------------

1.  引言
2.  API 的定义和用处
3.  Scanner
4.  Number
5.  Math
6.  Random
7.  ThreadLocalRandom
8.  Date
9.  DateFormat 和 SimpleDateFormat
10.  Calendar
11.  System

> **详见：[0：Base API](https://blog.csdn.net/qq_46207024/article/details/123195203?spm=1001.2014.3001.5501)**

1：Unit test and main function
-----------------------------

1.  抛出企业问题，脱离 main 测试，模块化编程
2.  Junit 单元测试的含义和用途
3.  怎么获取各种 Jar 包？Maven Repository 获取各类各个版本的 jar，这就是仓库。脱离老师发送给你的 jar。
4.  使用 Junit
5.  Assert 断言
6.  更进一步，合理编写随机测试，完善代码案例

> **详见：[1：Unit test and main function-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123608680)**

2：StringBuilder
---------------

1.  String 存在的问题
2.  Stringbuilder 以及链式调用的含义

> **详见：[2：StringBuilder-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123614722)**

3：Throwable
-----------

1.  异常的介绍
2.  异常举例以及解决常见错误 bug 方案
3.  RuntimeException
4.  trycatch 作用，闲扯淡诱骗毕业设计
5.  NullPointerException 空指针异常
6.  throws
7.  throws 和 trycatch 区别，用途区别
8.  手把手教你编写装 X 自定义异常

> **详见：[3：Throwable-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123616783)**

4：File
------

1.  引言
2.  绝对路径和相对路径？先学送快递吧！
3.  绝对路径
4.  相对路径
5.  File 类
6.  Linux 上的绝对路径有所不同

> **详见：[4：File-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123631771)**

5：IO Stream
-----------

1.  相对论和 IO 流之说
2.  汉语文学理解 IO 流
3.  图解 IO 流
4.  俩亲爹：InputStream 和 OutPutStream
5.  FileInputStream 字节流读取文件
6.  FileOutPutStream 字节流写入文件
7.  buff 缓冲复制文件
8.  buffered 字节缓冲流、装饰设计模式
9.  FileReader 和 FileWriter，俩专门来搞定 txt 文件
10.  BufferedReader、BufferedWriter
11.  一次性讲解剩余的 N 个流 (扩展课)Java 里那些极其骚的 IO 流
12.  Apache Common IO
13.  IO 流结束语

> **详见：[5：IO Stream-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123656123)**

6：CharSet
---------

1.  阶段
2.  字符集编码吹 X
3.  转换字符编码

> **详见：[6：CharSet-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123699142)**

7：Multithreading
----------------

1.  问题的提出
2.  核心数、进程、线程
3.  进程和线程的区别以及对应应用
4.  多线程程序含义、多线程的作用
5.  多线程的执行过程
6.  Runnable
7.  简化操作以及线程名
8.  抢购鞋——多线程案例
9.  后台、守护进程的提出
10.  匿名内部类创建多线程——你们老师喜欢的
11.  发现问题，提出 synchronized 的概念和用途
12.  synchronized 同步方法
13.  Lock、ReentrantLock 同步锁
14.  Unlock 遗留问题，释放锁
15.  浅谈 synchroized 和 Lock 的区别
16.  Thread API 说明
17.  CPU 线程调度、Priority 线程优先级、优先级常量、剩余小问题
18.  join 线程插队
19.  sleep 线程休眠
20.  yield 线程让步
21.  线程状态？嗯，还是来玩一盘游戏吧！
22.  发现实际问题，抛出线程通信的含义
23.  线程的通信：wait 和 notify
24.  notifyAll
25.  提及 Process 进程。点到为止，章节结束语和建议。

> **详见：[7：Multithreading-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123747979)**

8：Java Conllections FrameWork
-----------------------------

1.  原生数组带来的问题，抛出问题
2.  Conllections 家族
3.  黑帮的帮规
4.  ArrayList 第一讲
5.  ArrayList 第二讲
6.  ArrayList 第三讲
7.  Linked 链表
8.  LinkedList 一带而过
9.  提醒
10.  iterator 迭代器初试
11.  fori、增强 for、迭代器的区别、注意事项和分别用途
12.  谈谈三者性能
13.  Set 和 HashSet
14.  LinkedHashSet
15.  Map、HashMap、Entry
16.  Map 注意点
17.  Entry 与 Map 转换 Set 之后遍历： Iterator<Entry<Integer,Integer>> iterator = entrySet.iterator(); （什么？看不懂这行？）
18.  提及 LinkedHashMap 以及课后作业
19.  集合框架部分结束

> **详见：[8：Java Conllections FrameWork-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123809787)**

9：JDBC
------

1.  说明
2.  JDBC 的由来以及定义
3.  JDBC 体验，statement.executeQuery() 查询
4.  整理和释放
5.  封装 JDBCUtils
6.  增删改 —— executeUpdate()
7.  字符编码问题
8.  PreparedStatement 和问号占位符
9.  最终 Demo 说明
10.  对象的封装，重构代码， 学生管理系统模块化编程

> **详见：[9：JDBC-Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123932666?spm=1001.2014.3001.5501)**

10：Java 人脸识别认证
--------------

1.  提出问题，引入 SDK 的概念
2.  选择平台
3.  SDK 下载和文档说明
4.  人脸检测
5.  人脸对比
6.  建议和结束语

> **详见：[10：Java 人脸识别认证 - Java API 实战](https://blog.csdn.net/qq_46207024/article/details/123965821)**

结束语
---

下一步学习 Java Web

![](https://img-blog.csdnimg.cn/8c5d16a703804566ad732c97846660df.png)  
**该笔记由 [Yeats_Liao](https://blog.csdn.net/qq_46207024?type=sub&spm=1001.2014.3001.5348) 与 [Shea_Qiu](https://blog.csdn.net/weixin_45924718?type=blog) 共同完成**

**以上所有内容来自课程个人笔记：[面向对象大胆向前！Java API 实战 - Frank](https://www.yuque.com/frank-93a7b/fuck/lbz01b)**