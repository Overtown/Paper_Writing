# Paper_Writing
How to write a academic paper

## Tittle
题目一定表明你的论文亮点，好的题目具有以下特点：
1. 让人能够记住；
2. 能够快速理解；
3. 能够突出优势；

举个例子：Spatial Efficient Transformer for Image Restoration

## Abstract
摘要部分要介绍研究背景，解决的问题，提出的方法，创新点，方法结论。
整体可以采用总分总或总分的结构来介绍。
**注意事项：**
**1. 尽量快速进入到自己方法的介绍上；**
**2. 注意陈述实质，避免出现空泛的词汇，如：significant等**

### 背景和动机
背景和动机，尽量简单，一句话/两句话介绍明确、完整。
### 方法和创新点
介绍提出的方法，主要组成，方法重点能力。
80%～90%的篇幅需要来介绍方法。
### 结论
一句话，介绍方法的优势：
点清楚是计算精度上，计算复杂度上，还是计算效率上的优势
这部分要结合实验结果，点明对比sota方法的可量化优势

## Introduction
漏斗式的介绍，由浅入深逐步引入到你的问题以及解决方法上来。
### 背景介绍
介绍整体任务是什么，有什么作用。
介绍任务存在什么难点。
什么问题还没有被解决好。 
### 他人方法引入我们研究的问题
目前存在M1， M2， M3等方法，这些方法都是从什么角度进行解决的。
然而，（进一步引入到你要做的任务上），M1～M3 都没有解决好什么问题，导致了什么弊端。
或者方法有什么待提升的。
### 我们的insight
从而引出我们的方法：说下别人方法缺点的核心原因，我们发现了什么或者是怎么发现的。
### 创新点和结果
我们提出了一个什么方法，这个方法针对于以上问题，提出了什么创新点，能够在xx场景上，创新/巧妙的做一个什么事情，解决了这个问题，在xx任务上，进一步升精度。
列举和sota方法的精度-参数对比图，体现算法优势。
### Contributation
贡献点：
1. 针对于xx问题，提出xx方法，方法具有什么创新点。
2. 方法中核心模块能力或者迁移性/或者鲁棒性。
3. 客观指标对比。

## Related Work
相对详细介绍和总结下前人方法，突出方法的核心特点，优势。
**注意事项：**
**1. 避免过度攻击前人方法，委婉指出问题，阐明/引出我们研究重点即可。**
**2. 避免漏掉经典方法。**
需要分几个类别介绍，如：
1. 传统方法是什么，不足是啥。
2. CNN方法是哪些方法，不足是啥；
3. ViT的方法有哪些，不足；

## Methods
给出一个方法的overview，让人能够一眼看明白方法的工作流程或者核心创新点。
可以采用总-分的结构：
### Motivation/Overview
介绍方法的motivation，整体构成和推理pipeline;

### Module 1
详细介绍模块机制，组成，数学推导等。
### Module 2 
### Module 3
**注意事项：**
**1. 注意表达的简洁度，让人能够快速、清晰、明了掌握方法。**
**2. 注意公式或推导的缺失。**

## Results
数据形式：表格，柱状图，饼状图，折线图，特征可视化，处理结果可视化等。
**注意事项：**
**1. 避免数据形式过于单一，如只有table**
**2. 避免实验设定或者对比形式不公平**
分为两个部分：
1. 核心实验：介绍在任务上，与主流方法的对比，主客观指标；
2. 消融实验：介绍核心模块对于方法的影响，自证核心模块的有效性。

## Conclusion
一句话呼应为了解决什么问题，提出了一个什么方法。
一两句介绍，方法有什么作用/表现。
一句话总结实验结论。

## Reference
应用量在50～70篇。其中3～5年内论文占比在50%；
**注意事项：**
**引用的格式统一**
<img width="1560" alt="image" src="https://github.com/Overtown/Paper_Writing/assets/20881840/7fe1dff3-b559-49a3-abaa-efbac1020cda">


   
