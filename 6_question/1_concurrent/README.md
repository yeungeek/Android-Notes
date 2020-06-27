# Java并发多线程
* 描述synchronized和reentrantlock的底层实现以及重入的底层原理(百度 阿里)
* 描述锁的四种状态和升级过程(百度 阿里)
* CAS的ABA问题如何解决(百度)
* 请描述AQS，为什么AQS的底层是CAS+volatile(百度)
* volatile的理解(美团 阿里)
* volatile可见性和禁止指令重排序是如何实现的(美团)
* CAS是什么(美团)
* 请描述一下对象的创建过程(美团 顺丰)
* 对象在内存中的内存分布(美团 顺丰)
* DCL单例为什么要加 volatile(美团)
* 解释下锁的四种状态(顺丰)
* Object o = new Object()对象占用多少字节(顺丰)
* synchronized和reentrantlock的异同(顺丰)
* 聊一聊 as-if-serial和 happen-before语义的理解(京东)
* 是否了解ThreadLocal，以及ThreadLocal 中如何解决内存泄露问题(京东 阿里)
* 请描述锁的分类以及在 JDK 中的应用 (阿里)
* 自旋锁一定比重量级锁效果高吗?(阿里)
* 打开偏向锁是否效率一定会提升?为什么
---- 
美团深入问题：  
```
关于 Object o = new Object()
```
1. 解释对象的创建过程?(半初始化)
2. 加问 DCL 和 volatile 的问题?(指令重排)
3. 对象在内存中的存储布局?(对象与数组的存储不同)
4. 对象头包含的内容?(markwork kclass pointer),synchonized 锁信息
5. 对象怎么定位?(直接 间接)
6. 对象怎么分配?(栈上-线程本地-Eden-Old)
7. Object o = new Object()在内存中占用多少字节
----
* 说下对线程池的理解，以及创建线程池的几个关键参数
* 一个 int 变量用 volatile 修饰，多线程去操作 i++，是否线程安全？如何保证 i++ 线程安全？AtomicInteger 的底层实现原理？
* 实现一个线程同步的计数器
* 说一下对于线程安全的理解，Java中线程安全与不安全的集合类有那些？
* Java线程池默认提供了哪些类型？分别适合什么场景？
* Java线程中interrupt()、interrupted()和isInterrupted()分别代表什么意思？
* **JVM 内存区域 开线程影响哪块内存**
* 开启线程的三种方式,run()和start()方法区别
* static synchronized 方法的多线程访问和作用，同一个类里面两个synchronized方法，两个线程同时访问的问题
* 如何保证线程安全？
* 如何保证多线程读写文件的安全？
* 线程如何关闭，以及如何防止线程的内存泄漏
* 线程间 操作 List
* 如何停止一个正在运行的线程
* Java中用到的线程调度算法是什么？并作解释说明
* Java 对象的内存分配过程是如何保证线程安全的
* 守护线程与阻塞线程的四种情况
* 谈谈 Java 中多线程实现的几种方式
* 谈一谈线程sleep()和wait()的区别？
* 谈谈Java 线程中 notify 和 notifyAll有什么区别？
* 谈谈线程阻塞的原因？
* 谈谈线程死锁，如何有效的避免线程死锁？
* 如何实现多线程中的同步？

# 参考
* [Java并发面试题](https://github.com/JsonChao/Awesome-Android-Interview/blob/master/Java%E7%9B%B8%E5%85%B3/Java%E5%B9%B6%E5%8F%91%E9%9D%A2%E8%AF%95%E9%A2%98.md)
* [40个Java多线程问题详解复习](https://mp.weixin.qq.com/s/iEdLtwGVzdmNXqKKIHCDeA)
* [CodeEggDailyInterview](https://github.com/codeegginterviewgroup/CodeEggDailyInterview)
* [Android-Daily-Interview](https://github.com/Moosphan/Android-Daily-Interview)
