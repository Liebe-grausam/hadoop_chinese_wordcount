---
title: 计组期中兼MOOC梳理-1
date: 2024-03-30 23:24:47
tags: 计组
---
妈的GPT写的答案全错

![高亮为gpt，红笔为自己写的](../img/计组/选择题.png)

ljl的体系是mooc与上课课件正交的部分，，，

阿塔纳索夫研发的是ABC计算机，不是ENIAC。（2016期中）

第一台存储程序式电子计算机是EDSAC必考。（记忆点：S-save/store）

冯诺依曼五个基本组成部分必考。

>① 运算器， CA： central arithmetical
② 控制器， CC： central control
③ 存储器， M： memory
④ 输入设备， I： input
⑤ 输出设备， O： output

还有其他两个特点分别是：数据和程序均以二进制代码形式不加区别地存放在存储器中，存放位置由存储器的地址指定；计算机在工作时能够自动地从存储器中取出指令加以执行。

吗嘟这么多课件找不到的内容原来全在MOOC里！气死我了！

计算机执行指令的具体步骤：取指（Fetch），译码（Decode），执行（Execute），回写（Write-back）。（2017期中）

>取指：①控制器将指令的地址送往存储器 ②存储器按给定的地址读出指令内容，送回控制器
译码：①控制器分析指令的操作性质 ②控制器向有关部件发出指令所需的控制信号
执行：①控制器从通用寄存器或存储器取出操作数 ②控制器命令运算器对操作数进行指令规定的运算
回写：将运算结果写入通用寄存器或存储器

在 x86 实模式下， 假设 CS=3000H， DS=2000H，则指令“MOV AX,[3000H]” 执行时访问的内存地址是23000H。(2017期中) （MOOC课件上有原题一模一样）

>计算方法：DS*16+[3000H] 段地址×16＋偏移地址

按两个32位源操作数所在位置划分，MIPS和x86的加法指令都能够支持的是：寄存器 + 寄存器（2016期中）
>记住就行了，，默默插一嘴，这题也出现在MOOC的期末考试中，所以肯定是正确答案


