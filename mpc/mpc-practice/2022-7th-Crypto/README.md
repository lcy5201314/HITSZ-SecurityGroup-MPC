# 2022年第七届全国密码技术竞赛

## 1. 竞赛介绍

> 具体介绍见：[关于举办2022年第七届全国密码技术竞赛的通知](https://www.cacrnet.org.cn/site/content/1170.html)

### 1.1 竞赛流程

竞赛分为三个阶段：初赛、复赛和决赛。初赛和复赛在参赛单位的本地计算机终端上通过竞赛平台完成，决赛为现场评审。
1. 初赛：主要考查参赛学生对密码学基本知识、基础概念的理解和掌握程度，以客观题为主。基于浏览器/服务器（B/S）模式，参赛团队通过全国密码技术竞赛平台在本地完成在线答题。初赛后参赛团队通过竞赛官网查询初赛成绩。
2. 复赛：主要考查参赛学生对密码技术的综合运用与解决实际问题能力。参赛团队可选择组委会发布的复赛题目或自拟题目完成1个参赛作品，并在复赛截止时间之前通过竞赛平台提交作品，截止时间到系统自动关闭。竞赛平台对收集的每个复赛作品随机分配5名专家进行在线评审，取总评成绩作为该参赛团队的复赛成绩，成绩优异者进入决赛。
3. 决赛：主要考查决赛作品软件、硬件或系统的实际运行状况。决赛团队讲解并演示自己的软、硬件系统，组委会组织专家对决赛入围作品进行现场评审。

### 1.2 竞赛时间安排
1. 参赛注册：2022年9月1日17:00点前，领队老师登录2022第七届全国密码技术竞赛官方网站（ www.chinacodes.com.cn   ）在线注册参赛团队信息。
2．基本信息审核：2022年9月2-3日组委会对参赛团队信息进行审核。
3．竞赛报名：2022年9月7日（周三）17:00点前，领队老师通过竞赛平台提交本单位的报名信息表（报名信息表须加盖单位公章）。
4．初赛：2022年9月17日（星期六）9:00-18:00。一周后通知进入复赛名单，并进行复赛选题。（注：2022年8月20日开放初赛模拟练习系统，各参赛团队可登录大赛官网关注最新通知并进行模拟练习。）
5．复赛：2022年10月26日（周三）9:00到2022年10月28号（周五）17:00提交复赛作品。
6．决赛：2022年12月1-3日（1日报到）在国家网络安全人才与创新基地举行。

### 1.3 去年竞赛情况

参见[2021年第六届全国密码技术竞赛圆满落幕](https://www.cacrnet.org.cn/site/content/1104.html)

## 2. 参赛安排

+ 2022年8月16日-2022年9月17日：组织队伍参赛，介绍比赛流程和具体事项，简单准备初赛，同时讨论和确定复赛选题。
    + 8月16日-8月21日
    + 8月22日-8月28日
    + 8月29日-9月4日
        + **系统报名**（2022年9月1日17:00点前，领队老师登录2022第七届全国密码技术竞赛官方网站（  www.chinacodes.com.cn   ）在线注册参赛团队信息。）
        + **提交本单位的报名信息表**（2022年9月7日（周三）17:00点前，领队老师通过竞赛平台提交本单位的报名信息表（报名信息表须加盖单位公章）。）
        + 基于函数秘密共享的安全两方计算（杨鹏负责）、函数秘密共享的应用（庄杰航、高世祺负责）
            + 函数秘密共享的应用主要参考[RTPB22]ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing
                + 该论文是基于函数秘密共享的隐私保护深度学习，提出了针对于Equality Test、比较函数的函数秘密共享构造方案。
                + 其发表在PoPETs2022上，论文链接见[arXiv](https://arxiv.org/abs/2006.04593)、[PETS](https://petsymposium.org/popets/2022/popets-2022-0015.php)，代码链接见[GitHub](https://github.com/LaRiffle/ariann)、视频链接见[Youtube-vedio](https://www.youtube.com/watch?v=ztCptCgqZBs)
    + 9月5日-9月11日：协议构造和系统熟悉
        + 协议构造：优化AriaNN的协议，针对神经网络训练中涉及的运算设计相应协议（杨鹏负责）
        + 熟悉AriaNN的系统代码，并能够跑通代码（庄杰航、高世祺负责）
    + 9月12日-9月18日
        + **初赛**：2022年9月17日（星期六）9:00-18:00。
        + 并给出整个神经网络训练的协议，包括在线阶段和离线阶段（杨鹏负责）  --> 未完成
        + 函数秘密共享的应用（庄杰航、高世祺负责）
+ 2022年9月19日-2022年10月28日17:00：准备复赛作品（低层技术-系统框架-系统实现）
    + 9月19日-9月25日
        + 基于函数秘密共享的隐私保护神经网络协议（杨鹏负责） --> 未完成，正在了解神经网络训练流程
        + 密码技术竞赛选题材料撰写（庄杰航负责）
        + AriaNN代码跑通（高世祺）
    + 9月26日-10月2日
        + 基于函数秘密共享的隐私保护神经网络协议（杨鹏负责） 
        + 密码技术竞赛选题材料撰写（庄杰航负责）
        + AriaNN代码熟悉（高世祺）
    + 10月3日-10月9日
    + 10月10日-10月16日
    + 10月17日-10月23日
    + 10月24日-10月28日17:00
+ 2022年10月29日-2022年12月：进一步完善作品


