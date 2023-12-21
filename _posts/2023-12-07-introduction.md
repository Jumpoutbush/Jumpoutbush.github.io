---
title: 主要成果简介
author: dastro yang
date: 2023-12-07
category: Jekyll
layout: post

---

# [一、身份基加密](https://crypto2013.com/jekyll/2023-12-10-ibe.html)

## 	   ***代表性成果1：身份基加密紧归约问题***

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;紧归约：安全分析中所调用的底层假设实例的个数越少，安全归约越紧。归约越紧，归约损失越小，所设置的安全参数越小，方案运行时间越少。自双系统加密技术被提出以来，如何构造紧归约且适应性安全的IBE方案一直是一个公开问题。

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fully, (Almost) Tightly Secure IBE and Dual System Groups (CRYPTO 2013)](https://link.springer.com/chapter/10.1007/978-3-642-40084-1_25) 解决公钥领域多年来关于“身份基加密IBE紧归约”的公开问题。

<br>

# [二、属性基加密](https://crypto2013.com/jekyll/2023-12-11-abe.html)

## 		***代表性成果2：属性基加密ABE构造***

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;​加密方案构造有两个基本要求：1. 安全性  2. 效率。 在保证高级别的安全性前提下，尽可能地提升方案的效率。

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;​[Improved Dual System ABE in Prime-Order Groups via Predicate Encodings (EUROCRYPT 2015)](https://link.springer.com/chapter/10.1007/978-3-662-46803-6_20) 使用模块化的构造和多项创新技术，使ABE方案效率提升25%-50%。



## ***代表性成果3：无界属性基加密ABE***

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有界ABE：在系统开始的时候就设定属性空间。无界ABE：无需在系统开始的时候就设定属性空间。无界ABE方便更改属性空间。

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Unbounded ABE via Bilinear Entropy Expansion, Revisited (EUROCRYPT 2018)](https://link.springer.com/chapter/10.1007/978-3-319-78381-9_19) 提出新的“熵膨胀引理”，使得只需要用很少个数值就可以表达任意属性，大幅提高了无界ABE的效率



## 	***代表性成果4：ABE安全模型***

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ABE常见的安全模型对应的安全性有：适应性安全 > 选择性安全。是否存在折中的安全性，使得我们可以更好地了解适应性安全和选择性安全二者之间的空白地区，并且更好地扩大方案的应用场景？

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Semi-Adaptive Attribute-Based Encryption and Improved Delegation for Boolean Formula (SCN 2014)](https://link.springer.com/chapter/10.1007/978-3-319-10879-7_16) 提出了“半适应性semi-adaptive安全模型”，在主公钥（或者公共参数）被给出之后再确认挑战属性。

<br>

# [三、身份匹配加密IB-ME](https://crypto2013.com/jekyll/2023-12-12-ibme.html)

## 	***代表性成果6：身份匹配加密IB-ME构造***

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;普通的匿名IBE只能做到对接收方的匿名身份验证，当需要对发送方和接收方进行双重匿名身份验证时，就需要IBME。在此之前存在的IBME要么要求随机喻言机模型，要么基于不标准的底层假设。能否构造一个在标准模型下、基于标准假设的身份匹配加密方案？

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Identity-Based Matchmaking Encryption from Standard Assumptions (ASIACRYPT 2022)](https://link.springer.com/chapter/10.1007/978-3-031-22969-5_14) 提出了首个标准模型、标准假设下的IBME方案主要技术：巧妙的、非黑盒的双层匿名IBE的代数构造。对双系统加密证明技术的新式运用。

<br>

# [四、内积加密IPE](https://crypto2013.com/jekyll/2023-12-12-ipe.html)

## 	***代表性成果5：内积加密IPE构造***

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;完全属性隐藏的适应性安全是目前IPE能达到的最高的安全性。但是安全性的提高往往伴随着效率的问题。能否进一步提高已有的完全属性隐藏的适应性安全的IPE方案的效率？

​​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Improved Inner-product Encryption with Adaptive Security and Full Attribute-hiding (ASIACRYPT 2018)](https://link.springer.com/chapter/10.1007/978-3-030-03329-3_23) 对于MDDH假设的进一步的详细的理论分析，对full attribute-hiding IPE的构造进行了改进，效率得到了提高。



