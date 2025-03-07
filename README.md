

# Useful_Asic_Design_Resources

以下记录我自己在学习数字IC非常有用的资料

## 个人认为数字IC学习分为几个阶段



1. 婴儿期：Verilog 和 C++ 的区别分不开，知道Verilog是给硬件的编程语言
2. 炼体期：理解可综合的Verilog代码，对基本的数字电路设计有认识，对FSM，FIFO理解了一个大概，对整个数字IC的流程有一个大概
3. 筑基期：能手撕一个RISCV，对于RTL反应到后端的电路有一定理解，对于DC综合语句有一定的理解，对于数字后端有一定的理解
4. 金丹期：能把RISCV全流程一个人跑完，能把每一行综合，后端语句理解清楚，能掌握Computer Architecture里面的入门思想，能写一些奇怪的RTL代码
5. 伪婴期：尝试对数字IC中不同的工作细分领域更深一层，主要分为：数字前端设计Design，数字前端验证DV，数字中端STA/DC，数字后端PR，成功找到大厂当牛马继续学习
6. 元婴期：在职场工作几年还在不断学习的大佬。。。对于自己的业务清楚无比。。。



### 1. Verilog 基础

先从基础中的基础开始，嘿嘿，免得写一些不可综合的代码 = =

个人理解，入门Verilog，一般都是大家不得不写Verilog。。。比如课设的作业，大家可以参考着这些写

> [!CAUTION]
>
> 不过时刻记住！Verilog HDL（简称 Verilog ）是一种**硬件描述**语言，不是软件，是描述的硬件电路！

1. HDLBits --[HDLBits](https://hdlbits.01xz.net/wiki/Main_Page)

​	一个简单的Verilog入门网站，有大量的练习，对于新手来说十分友好，但是稍微有点点基础

2. The Verilog Golden Reference Guide --https://class.ece.iastate.edu/cpre488/resources/verilog_reference_guide.pdf

​	大佬写的，欣赏就完了，基础不是很好可能读起来比较困难

3. RUNOOB --[1.1 Verilog 教程 | 菜鸟教程](https://www.runoob.com/w3cnote/verilog-tutorial.html)

   好用的一批！

### 2. IC Design 基础

1. Useful Books

   1. "Crack the Hardware Interview" "CMOS VLSI Design"--https://picture.iczhiku.com/resource/eetop/syiWFAeQEZAEPvVX.pdf

   2. “Computer Architecture A Quantitative Approach" --https://acs.pub.ro/~cpop/SMPA/Computer%20Architecture%20A%20Quantitative%20Approach%20(5th%20edition).pdf

2. From RTL to GDS

3. IC Design Flow -- https://www.cnblogs.com/sasasatori/p/18325095

4. 面试很有用的，以及适合入门IC的视频讲解 -- https://space.bilibili.com/354403348?spm_id_from=333.337.0.0

### 3. 综合/DC/STA

1. Tcl and Design Complier and Physical Design - https://www.cnblogs.com/IClearner/category/972492.html

​	就这一个就很够入门了！

### 4. 总线协议

1. AXI：https://developer.arm.com/documentation/ihi0022/latest/

   最经典也是最官方的也是最好用的

2. AXI B站讲解：https://www.bilibili.com/video/BV1yP12YdErw/?spm_id_from=333.337.search-card.all.click&vd_source=32450aacac114d3dcdb1451b2f50b594

​	强烈推荐，从入门到深入都可以看

3. AHB，APB，SPI，UART，可以自己写一些，主要参考Spec吧

### 5. Computer Architecture

个人理解，写一个RISCV，然后再尝试理解计算机架构的思想

1. Oner Mutlu --https://course.ece.cmu.edu/~ece447/s15/doku.php?id=start

​	最好的入门，也是最好的深入，不过建议写过RISCV核再来细看，更有更多收获

​	还有一个全新版：https://safari.ethz.ch/architecture/fall2023/doku.php?id=schedule

2. GPU Architecture https://zhuanlan.zhihu.com/p/706977082

## ASIC

## Design Verification

- SV & UVM - https://verificationguide.com/systemverilog/introduction/

## Tools & Programming Language

- Makefile - https://liaoxuefeng.com/books/makefile/prerequisites/index.html  
