---
layout: post
title: "Test for Markdown"
date: 2017-10-06
categories: Test
tags: [TeX, jekyll]
image: 
---

## Test

### 中文测试

#### 千字文

千字文

> 天地玄黄 宇宙洪荒 日月盈昃 辰宿列张
>
> 寒来暑往 秋收冬藏 闰馀成岁 律吕调阳
>
> 云腾致雨 露结为霜 金生丽水 玉出昆冈

### MathJex测试

质能方程：
\\[ \Delta E= \Delta m c^2\\]

求和：
\\[\sum_{i=1}^n{i^2}=\frac{n(n+1)(2n+1)}{2}\\]


### 表格测试

|排序算法|时间复杂度|
|---|---|
|冒泡排序|$O(n^2)$|
|插入排序|$O(n^2)$|
|快速排序|$O(n \log n)$|

### 图片测试

![测试图片](/assets/images/post/yinhuajie1.jpg)

### 代码测试

```python
def fib(n):
  if n<=1: return 1
  return fib(n-1)+fib()
```
{% highlight cpp linenos %}

/**
 * LinkNode struct defination
 * The node in Linked List.
 */
template <class Type>
struct LinkNode {
    Type data;
    LinkNode<Type> *next;
    LinkNode(LinkNode<Type> *ptr = NULL) { next = ptr; }
    LinkNode(const Type &item, LinkNode<Type> *ptr = NULL) {
        data = item;
        next = ptr;
    }
};

{% endhighlight %}
## 综合

### 稀缺性

稀缺性的力量源于：
1. 对经验依赖：根据获得东西的难易程度来迅速准确地判断质量
2. 既得利益的保护：当机会越来越少时，我们的自由也在丧失，**保护既得利益是逆反的核心**

例子：

* 两岁男孩的行为，直接挑衅
    * 表现：对于限制自由时的反抗行为
    * 原因：他们正在体验独立的人类个体
    * 意义：对信息的求索，关于选择、权利和控制，**测试自由的极限在哪里。**


