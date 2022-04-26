# HITSZ安全组—MPC团队
多学习，多思考，多实践！

## MPC团队介绍
HITSZ安全组的MPC团队主要针对安全多方计算的理论与实践进行研究。

## 什么是安全多方计算？
安全多方计算(Secure Multi-Party Computation，MPC)起源于姚期智提出的“百万富翁问题”，并发展至今，成为了隐私计算领域的一项重要工具。姚期智在1982年借百万富翁问题提出安全两方计算的概念，并在1986年引入混淆电路协议(Garbled Circuits Protocol，GC)初步解决安全两方计算的问题，混淆电路协议至今都是许多最有效的MPC实现的基础，Goldreich等人在1987年针对多方参与的情况进行了分析。而后的20多年里，安全多方计算一直处于理论研究阶段，直至21世纪初，随着算法不断的改进和算力不断的提升，考虑使用通用多方计算(General purpose multiparty computation)构建实际系统变得现实。如今，安全多方计算在金融、医疗、银行、政务等领域已经有了广泛的应用。

## 安全多方计算(MPC)的基本框架
+ 基本概念
  + MPC基本概念
  + 安全性定义
  + 安全性证明
+ 基础模块
  + 不经意传输(Oblivious Transfer, OT)：基础OT和OT扩展
  + 秘密共享(Secret Sharing, SS)：门限秘密共享和加性秘密共享
  + 混淆电路(Garbled Circuits, GC)
  + 剪切-选择技术(Cut-and-Choose)
  + 零知识证明(Zero Knowledge Proof)
  + 同态加密(Homomorphic Encryption)
+ 经典协议
  + 混淆电路协议[Yao86]
  + GMW协议[GMW87]
  + BGW协议[BGW88]
  + BMR协议[BMR90]
  + ...
+ 通用协议框架
  + 基于混淆电路的MPC协议
  + 基于秘密共享的MPC协议
  + 基于同态加密的MPC协议
  + 混合协议
    + SPDZ框架：基于秘密共享和有限同态加密的协议框架
    + ABY系列：基于布尔电路、算术电路和混淆电路的协议框架，包括ABY、ABY3和ABY2.0
+ 应用研究
  + 隐私集合操作(Private Set Operation)
  + 隐私保护数据挖掘(Privacy Preserving Data Mining)
  + 隐私保护机器学习(Privacy Preserving Machine Learning)
  + ...

## 如何学习安全多方计算？
+ MPC大牛的学习经验
  + [Yehuda Lindell](https://u.cs.biu.ac.il/~lindell/)谈如何学习安全多方计算
    + [Resources for Getting Started with MPC](https://u.cs.biu.ac.il/~lindell/MPC-resources.html)
    + 综述文章[Secure Multiparty Computation (MPC)](https://eprint.iacr.org/2020/300.pdf)
  + [Mike Rosulek](https://web.engr.oregonstate.edu/~rosulekm/)谈论如何入门学习安全多方计算
    + [An Annotated Bibliography of Practical Secure Computation](https://web.engr.oregonstate.edu/~rosulekm/scbib/index.php?n=Main.GettingStarted)
+ MPC课程学习(更多详见mpc-resource)
  + 第一届BIU密码学冬令营：安全多方计算与效率
    + [The 1st BIU Winter School: Secure Computation and Efficiency (01/30 - 02/01, 2011)](https://cyber.biu.ac.il/event/the-1st-biu-winter-school/)
  + 第五届BIU密码学冬令营：实用安全多方计算进展
    + [The 5th BIU Winter School: Advances in Practical Multiparty Computation (02/15 – 02/19, 2015)](https://cyber.biu.ac.il/event/the-5th-biu-winter-school/)
  + [Arpita Patra](https://www.csa.iisc.ac.in/~arpita/index.html)关于安全多方计算的课程
    + [Secure Computation 2015](https://www.csa.iisc.ac.in/~arpita/SecureComputation15.html)
    + [Secure Computation 2017](https://www.csa.iisc.ac.in/~arpita/FoSC17.html)
+ MPC相关书籍(更多详见mpc-resource)
  + [[Evans et al.2018]A Pragmatic Introduction to Secure Multi-Party Computation](https://securecomputation.org/)
    + 该书概述了安全多方计算中的定义、基本工具和经典协议，并调查了提高使用 MPC 构建的隐私保护应用程序效率的方法。除了对该领域的广泛概述和主要结构的见解外，还概述了当前最活跃的MPC研究领域，旨在让读者深入了解当今使用MPC可以实际解决哪些问题，以及不同的威胁模型和假设如何影响 不同方法的实用性。
  + [[Hazay&Lindell2010]Efficient Secure Two-Party Protocols](https://u.cs.biu.ac.il/~lindell/efficient-protocols.html)
    + 该书详细介绍了安全两方计算的基本概念，和相关的工具和技术。
    + [Download](https://link.springer.com/book/10.1007/978-3-642-14303-8)
