# C++ 并发编程指南 #
本书计划分为 11 章, 分别如下安排:

* 第一章 并发编程基础 *

    * 1.1 [什么是并发编程](zh/chapter1-Introduction/1.1 What is concurrency.md) 
    * 1.2 [并发与并行的区别和联系](zh/chapter1-Introduction/1.1 What is concurrency.md)
    * 1.3 为什么需要并发编程
    * 1.4 并发编程应用场景和经典示例
    * 1.5 [C++ 并发编程初探](zh/chapter1-Introduction/Cplusplus-Concurrency-Introduction.md)
    * 1.6 [资料汇](zh/chapter1-Introduction/web-resources.md)


* 第二章 几种常见的多线程库介绍

    * 2.1 Pthread 多线程编程指南

    * 2.2 Windows 多线程编程指南

    * 2.3 几种常见的多线程库接口对比

    * 2.4 资料汇


* 第三章 线程详解

    * 3.1 [`<thread>` 头文件摘要](zh/chapter3-Thread/Introduction-to-Thread.md)

    * 3.2 [`std::thread` 详解](zh/chapter3-Thread/Introduction-to-Thread.md#stdthread-%E8%AF%A6%E8%A7%A3)

    * 3.3 [`std::this_thread` 命名空间中相关辅助函数介绍](zh/chapter3-Thread/Introduction-to-Thread.md)

    * 3.4 `std::thread` 与 Pthread 线程对比

    * 3.5 [资料汇](zh/chapter3-Thread/web-resources.md "资料汇")


* 第四章 互斥量与锁

    * 4.1 [`<mutex>` 头文件摘要](zh/chapter4-Mutex/4.1 Mutex-header-synopsis.md)

    * 4.2 [互斥量详解](zh/chapter4-Mutex/4.2 Mutex-tutorial.md)

    * 4.3 [锁类型详解](zh/chapter4-Mutex/4.3 Lock-tutorial.md

    * 4.4 辅助函数介绍

    * 4.5 `std::mutex` 与 Pthread 互斥量对比

    * 4.6 [资料汇](zh/chapter4-Mutex/web-resources.md)


* 第五章 条件变量与线程同步

    * 5.1 [`<condition_variable>` 头文件摘要](zh/chapter5-Condition-Variable/5.1 Condition-variable header synopsis.md)

    * 5.2 [条件变量详解](zh/chapter5-Condition-Variable/5.2 Condition-variable-tutorial.md)     *

    * 5.3 [辅助函数介绍](zh/chapter5-Condition-Variable/5.3 Auxiliary-function.md)

    * 5.4 利用条件变量（std::condition_variable）进行线程同步 

    * 5.5 `std::condition_variable` 与 Pthread 条件变量对比

    * 5.6 [资料汇](zh/chapter5-Condition-Variable/web-resources.md)


* 第六章 异步任务详解

    * 6.1 [`<future>` 头文件摘要](zh/chapter6-Future/6.1 Future-header-synopsis.md)

    * 6.2 [异步任务提供者(Provider) 介绍](zh/chapter6-Future/6.2 Providers-tutorial.md)

    * 6.3 [异步任务提供者(Provider) 介绍（续）](zh/chapter6-Future/6.3 Providers-tutorial-2.md)

    * 6.4 [异步任务 Future 类型详解](zh/chapter6-Future/6.4 Future-tutorial.md)

    * 6.5 [与异步任务相关的类型介绍](zh/chapter6-Future/6.5 Auxiliary-types.md)

    * 6.6 [异步任务辅助函数 `std::async` 介绍](zh/chapter6-Future/6.6 Auxiliary-function.md)

    * 6.7 异步任务与多线程实例

    * 6.8 [资料汇](zh/chapter6-Future/web-resources.md)


* 第七章 原子类型详解

    * 7.1 [`<atomic>` 头文件摘要](zh/chapter7-Atomic/7.1 Atomic-header-synopsis.md)

    * 7.2 [`std::atomic_flag` 详解](zh/chapter7-Atomic/7.2 Atomic-flag-tutorial.md)

    * 7.3 [基本 `std::atomic` 类型详解](zh/chapter7-Atomic/7.3 Atomic-tutorial.md)

    * 7.4 [特化的 `std::atomic` 类型详解](zh/chapter7-Atomic/7.4 Atomic-tutorial2.md)

    * 7.5 [C 风格的原子操作](zh/chapter7-Atomic/7.5 C-style-atomic.md)

    * 7.6 C++11 内存模型初探

    * 7.7 如何利用原子类型设计并发数据结构

    * 7.8 [资料汇](zh/chapter7-Atomic/web-resources.md)


* 第八章 C++11 内存模型

    * 8.1 C++ 内存模型概述
    * 8.2 X86 CPU 处理器架构与常见的存储一致性模型简介
    * 8.3 内存序（Memory Order）与同步操作
    * 8.4 原子类型编程实例
    * 8.5 Lock-free 编程初探
    * [资料汇](zh/chapter8-Memory-Model/web-resources.md)


* 第九章 高级线程管理


* 第十章 如何编写正确的并发数据结构


* 第十一章 并发编程应用实例

    * 11.1 [利用 C++11 并发设施解决生产者消费者问题](zh/chapter11-Application/11.1 Producer-Consumer-solution.md "如何利用 C++11 并发设施解决生产者消费者问题")


* 附录 C++11 新标准概览

    * 1. [核心语言的运行时性能强化](zh/appendix C++11 standards/C++11 Core language runtime performance enhancements.md)

    * 2. [核心语言的构建时性能强化](zh/appendix C%2B%2B11 standards/C%2B%2B11 Core language build time performance enhancements.md)

本小节主要包括：

1. 外部模板。

    * 3. [核心语言的可用性强化](zh/appendix C%2B%2B11 standards/C%2B%2B11 Core language usability enhancements.md)
