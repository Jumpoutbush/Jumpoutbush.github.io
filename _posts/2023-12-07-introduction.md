---
title: 主要成果简介
author: dastro yang
date: 2023-12-07
category: Jekyll
layout: post

---

# 身份基加密

## 	   ***代表性成果1：身份基加密紧归约问题***

​		自IBE提出以来，最核心的公开问题是：如何在标准模型（不使用随机预言机RO）、标准假设、适应性安全模型下设计具有紧归约的IBE方案。减少归约损耗不仅具有很强的理论意义，对实践应用也非常重要：为了确保相同的安全性，需要用更大的安全参数来弥补归约损耗，换句话说方案的运行效率也会变低。该工作创新地结合伪随机函数技术，在双系统加密中将密文和私钥按照id逐比特转换，最终使得安全损失只取决于安全参数，与秘钥问询次数无关；并由此基于素数阶群上的DLIN假设给出了第一个同时具备上述四个特性的IBE方案。

 1. [Fully, (Almost) Tightly Secure IBE and Dual System Groups (CRYPTO 2013)](https://link.springer.com/chapter/10.1007/978-3-642-40084-1_25)

    解决公钥领域多年来关于“身份基加密IBE紧归约”的公开问题。

    ***主要技术：***

    ​		结合伪随机函数的技术，在双系统加密中将密文和私钥按照id逐比特转换。

    ***其他相关工作：***

 2. [Efficient IBE with Tight Reduction to Standard Assumption in the Multi-challenge Setting (ASIACRYPT 2016)](https://link.springer.com/chapter/10.1007/978-3-662-53890-6_21)

 3. [Tightly Secure IBE Under Constant-Size Master Public Key (PKC 2017)](https://link.springer.com/chapter/10.1007/978-3-662-54365-8_9)

 4. [Extended Nested Dual System Groups, Revisited(PKC 2016)](https://link.springer.com/chapter/10.1007/978-3-662-49384-7_6) 

# 属性基加密

## 		***代表性成果2：属性基加密ABE构造***

​		加密方案构造有两个基本要求：1. 安全性  2. 效率。 在保证高级别的安全性前提下，尽可能地提升方案的效率。

5. [Improved Dual System ABE in Prime-Order Groups via Predicate Encodings (EUROCRYPT 2015)](https://link.springer.com/chapter/10.1007/978-3-662-46803-6_20)

   模块化的构造和多项创新技术，使ABE方案效率提升25%-50%。

   ***主要技术：***

       1. 全新的从合数阶群至素数阶群的模拟技术。
    
       2. 利用谓词编码将ABE的素数阶群下的构造模块化。

   

   ## ***代表性成果3：无界属性基加密ABE***

   ​	有界ABE：在系统开始的时候就设定属性空间。无界ABE：无需在系统开始的时候就设定属性空间。无界ABE方便更改属性空间。

6. [Unbounded ABE via Bilinear Entropy Expansion, Revisited (EUROCRYPT 2018)](https://link.springer.com/chapter/10.1007/978-3-319-78381-9_19)

   提出新的“熵膨胀引理”，大幅提高了无界ABE的效率

   ***主要技术：***
   　　提出新的“熵膨胀引理”，使得只需要用很少个数值就可以表达任意属性。

   ***其他相关成果：***

7. [ABE with Tag Made Easy (ASIACRYPT 2017)](https://link.springer.com/chapter/10.1007/978-3-319-70697-9_2)

8. [Improved Fully Adaptive Decentralized MA-ABE for NC1 from MDDH (ASIACRYPT 2023)]()

9. [The Relation and Transformation Between HIPE and SE (Designs Codes and Cryptography 2014)]()

10. [Spatial Encryption Supporting Non-Monotone Access Structure (Designs Codes and Cryptography 2014)]()

11. [Extended Dual System Group and Shorter Unbounded Hierarchical Identity Based Encryption (Designs, Codes and Cryptography)](https://link.springer.com/article/10.1007/s10623-015-0117-z)

12. [Leakage-resilient Attribute Based Encryption in Prime-order Groups via Predicate Encodings (Designs, Codes and Cryptography)](https://link.springer.com/article/10.1007/s10623-017-0399-4)

13. [Shorter IBE and Signatures via Asymmetric Pairings (Pairing 2012)](https://link.springer.com/chapter/10.1007/978-3-642-36334-4_8)

14. [Doubly Spatial Encryption from DBDH (Theoretical Computer Science)](https://www.sciencedirect.com/science/article/pii/S0304397514004277)

15. [Public key encryption with equality test via hash proof system (Theoretical Computer Science)](https://www.sciencedirect.com/science/article/pii/S0304397519303822)

16. [Non-Zero Inner Product Encryption with Short Ciphertexts and Private Keys (SCN 2016)](https://link.springer.com/chapter/10.1007/978-3-319-44618-9_2)



## 	***代表性成果4：ABE安全模型***

​		ABE常见的安全模型对应的安全性有：适应性安全 > 选择性安全。是否存在折中的安全性，使得我们可以更好地了解适应性安全和选择性安全二者之间的空白地区，并且更好地扩大方案的应用场景？

17. [Semi-Adaptive Attribute-Based Encryption and Improved Delegation for Boolean Formula (SCN 2014)](https://link.springer.com/chapter/10.1007/978-3-319-10879-7_16)

    提出了“半适应性semi-adaptive安全模型”

    ***主要技术：***
    　　在主公钥（或者公共参数）被给出之后再确认挑战属性。



## 	***代表性成果5：内积加密IPE构造***

​		完全属性隐藏的适应性安全是目前IPE能达到的最高的安全性。但是安全性的提高往往伴随着效率的问题。能否进一步提高已有的完全属性隐藏的适应性安全的IPE方案的效率？

18. [Improved Inner-product Encryption with Adaptive Security and Full Attribute-hiding (ASIACRYPT 2018)](https://link.springer.com/chapter/10.1007/978-3-030-03329-3_23)

    对full attribute-hiding IPE的构造进行了改进，效率得到了提高

    ***主要技术：***
    　　对于MDDH假设的进一步的详细的理论分析。



## 	***代表性成果6：身份匹配加密IB-ME构造***

​		普通的匿名IBE只能做到对接收方的匿名身份验证，当需要对发送方和接收方进行双重匿名身份验证时，就需要IBME。在此之前存在的IBME要么要求随机喻言机模型，要么基于不标准的底层假设。

​		能否构造一个在标准模型下、基于标准假设的身份匹配加密方案？

19. [Identity-Based Matchmaking Encryption from Standard Assumptions (ASIACRYPT 2022)](https://link.springer.com/chapter/10.1007/978-3-031-22969-5_14) 

    提出了首个标准模型、标准假设下的IBME方案

    ***主要技术：***

      1. 巧妙的、非黑盒的双层匿名IBE的代数构造。

      2. 对双系统加密证明技术的新式运用。

         