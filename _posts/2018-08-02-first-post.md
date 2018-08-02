---
layout: post
title: david silver课程笔记七
image: /img/hello_world.jpeg
---

主要介绍一下david大神的[强化学习课程](https://space.bilibili.com/74997410/#/),课程本身质量很不错，但是翻译水平实在很差，极大的加深了理解的难度．　

**第七讲的中心思想是参数化policy,通过一系列梯度算法来优化policy.**  
与基于value的算法相比，policy gradient最大的优势莫过于能够有效的处理连续行动空间的策略优化．至于它所被诟病的效率低，方差大等问题，都可以被后来的加强版policy gradient解决. 

policy gradient的主要流程就是  
                            1. 评价policy  
                            2. 根据评价梯度改善policy  

