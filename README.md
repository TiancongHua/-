# 算法笔试题技巧汇总

### 技巧1：
当题目中出现了num=x**n的时候，要立即想到n=math.log(num,x),可以很快速地解决最大边界问题。

### 技巧2：
利用set可以确定数组中是否有重复的元素。结合字符串的 str.count(),可以确定是哪一个字符出现了多次。

### 技巧3：引用自（https://github.com/cy69855522/Shortest-LeetCode-Python-Solutions）
set 中的 in 操作时间复杂度为 O(1)
dict.get 可以设置预设值，避免取到不存在的 key 时报错
遇到关于数组的问题，不妨先想想是否应该先排序
最短路径搜索问题通常使用 bfs
迭代器是缩小 space efficiency 的利器
让数字在一定范围内循环递增常常使用 % 操作
a << b 相当于 a * 2**b，a >> b 相当于 a // 2**b
