# 目录

- source code: http://www.javaconcurrencyinpractice.com

### 第一章：简介

- [x] 线程的优势
- [x] 线程的风险

## 基础部分
### 第二章：线程安全性

- [ ] 原子性
- [ ] 加锁
- [ ] 用锁来保护状态
- [ ] 活跃性与性能

### 第三章：对象的共享

- [ ] 可见性
- [ ] 发布与逸出
- [ ] 线程封闭
- [ ] 不变性
- [ ] 安全发布

### 第四章：对象的组合

- [ ] 设计线程安全的类
- [ ] 实例封闭
- [ ] 线程安全性的委托
- [ ] 在现有线程安全类中添加功能

### 第五章：基础构建模块

- [ ] 同步容器
- [ ] 并发容器
- [ ] 阻塞队列和生产者-消费者模式
- [ ] 阻塞与中断方法
- [ ] 同步工具类
- [ ] 构建高效可伸缩的结果缓存

## 结构化并发应用程序
### 第六章：任务执行

- [ ] 在线程中执行任务
- [ ] Executor框架
- [ ] 找出可利用的并行性

### 第七章：取消与关闭

- [ ] 任务取消
- [ ] 停止基于线程的任务
- [ ] 非正常的线程终止
- [ ] JVM 关闭

### 第八章：线程池

- [ ] 在任务与执行策略之间的隐性耦合
- [ ] 设置线程池大小
- [ ] 设置ThreadPoolExecutor
- [ ] 扩展ThreadPoolExecutor
- [ ] 递归任务并行化

## 活跃性，性能与测试
### 第十章：避免活跃性危险

- [ ] 死锁
- [ ] 死锁的避免与诊断
- [ ] 其他活跃性危险

### 第十一章：性能和可伸缩性

- [ ] 对性能的思考
- [ ] Amdah1定律
- [ ] 线程开销
- [ ] 减少锁的竞态
- [ ] 比较Map的性能
- [ ] 减少上下文切换的开销

### 第十二章：并发程序测试

- [ ] 正确性的测试
- [ ] 性能测试
- [ ] 避免性能测试陷阱
- [ ] 其他测试方法

## 高级主题
### 第十三章：显示锁

- [ ] Lock 与ReentrantLock
- [ ] 性能考虑因素
- [ ] 公平性
- [ ] Synchronized与ReentrantLock
- [ ] 读写锁

### 第十四章：构建自定义的同步工具

- [ ] 状态依赖性的管理
- [ ] 使用条件队列
- [ ] 显示的Condition对象
- [ ] Synchronizer
- [ ] AbstractSynchronizer
- [ ] concurrent同步器AQS

### 第十五章：原子变量与非阻塞同步机制

- [ ] 锁的劣势
- [ ] 硬件对并发的支持
- [ ] 原子变量类
- [ ] 非阻塞算法

## 第十六章：Java 内存模型

- [ ] 什么是内存模型
- [ ] 发布
- [ ] 初始化过程中的安全性
