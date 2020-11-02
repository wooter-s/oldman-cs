stack-and-queue


## 学习目的



## 结构

- 栈
  - 概念
  - 结构
    - 顺序栈
    - 链式栈
  - 栈的应用
- 队列
  - 概念
  - 结构
    - 链式队列
    - 顺序队列



## 名词解释



## 知识点



#### 栈

基本操作

**Initstack(s)** 置为空栈

**Push(s, e)** e进栈s; if (s) 已满，会发生溢出；

**Pop(s, e)** 弹出栈顶元素， 拷贝到给e；if (s) 空栈，发生”下溢“（underflow）

**Gettop(s,e)**栈s的顶不元素拷贝到e

**Empty(s)** 是否是空栈boolean



##### 固定进栈顺序，输出的可能顺序是什么？

输入(..., ai, ..., aj, ..., ak, ...) 不可能输出 (..., ak, ..., ai, ..., aj, ...);

一句话， 后入的元素先出， 则后入的元素前的元素顺序不能修改



输入

​	ABC

排列组合：

​	ABC 

​	ACB 

​	BAC

​	BCA

​	CAB

​	CBA

不可能出现的是 CAB





#### 顺序栈

用书序空间表示的栈



设计方案主要考虑

- 如何分配存储空间
  - 动态分配还是静态分配
  - 栈的空间范围
- 如何设置进栈和出栈的标志top
- 分析满栈条件
- 分析空栈条件



## 纠错测试

#### 第一次测试

![stack-queue-first-test](./stack-queue-first-test.jpg)



#### 第二次测试

![stack-queue-second-test](./stack-queue-second-test.jpg)

#### 错误类型

- [ ] 栈
  - [x] 进出栈限制
  - [x] 进出栈数据操作(可以在数组底部或者顶部开始， 然后++ 或者--进行操作)
  - [ ] 链式栈，数据结构
- [ ] 队列
  - [ ] 链式队列数据结构
  - [x] 链式队列空判断（带结点front==rear，不带结点front == null）

### 扩展

[前缀、中缀、后缀表达式](https://zhuanlan.zhihu.com/p/37467928)

## 应用















