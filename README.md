# base-data-structure
## 8种常用数据结构
1. 数组
2. 栈
3. 队列
4. 链表
5. 图
6. 树
7. 前缀树
8. 哈希表
### 1. 数组
数组(Array)大概是最简单，也是最常用的数据结构了。其他数据结构，比如栈和队列都是由数组衍生出来的。
### 数组的基本操作
- Insert - 在某个索引处插入元素
- Get - 读取某个索引处的元素
- Delete - 删除某个索引处的元素
- Size - 获取数组的长度
### 常见数组代码面试题
- [查找数组中第二小的元素](https://www.geeksforgeeks.org/to-find-smallest-and-second-smallest-element-in-an-array/)
- [查找第一个没有重复的数组元素](https://www.geeksforgeeks.org/non-repeating-element/)
- [合并 2 个排序好的数组](https://www.geeksforgeeks.org/merge-two-sorted-arrays/)
- [重新排列数组中的正数和负数](https://www.geeksforgeeks.org/rearrange-positive-and-negative-numbers-publish/)

### 2.栈
撤回，即 Ctrl+Z，是我们最常见的操作之一，大多数应用都会支持这个功能。你知道它是怎么实现的吗？答案是这样的：把之前的应用状态(限制个数)保存到内存中，最近的状态放到第一个。这时，我们需要栈(stack)来实现这个功能。
栈中的元素采用 LIFO (Last In First Out)，即后进先出
### 栈的基本操作
- Push —  在栈的最上方插入元素
- Pop — 返回栈最上方的元素，并将其删除
- isEmpty —  查询栈是否为空
- Top —  返回栈最上方的元素，并不删除
### 常见的栈代码面试题
- [使用栈计算后缀表达式](https://www.geeksforgeeks.org/stack-set-4-evaluation-postfix-expression/)
- [使用栈为栈中的元素排序](https://www.geeksforgeeks.org/sort-stack-using-temporary-stack/)
- [检查字符串中的括号是否匹配正确](https://www.geeksforgeeks.org/check-for-balanced-parentheses-in-an-expression/)
### 3. 队列
队列(Queue)与栈类似，都是采用线性结构存储数据。它们的区别在于，栈采用 LIFO 方式，而队列采用先进先出，即FIFO(First in First Out)。
