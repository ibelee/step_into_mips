## 预备知识和基本器件

计算机组成原理课程需要具备一定的数字电路知识（主要为前导课程《数字逻辑》内容），其中需要掌握以下基础知识。

1. 数值表示和数制，重点是二进制数、十六进制数。
2. 数值的原码表示和补码表示，有符号数、无符号数，溢出。
3. 基本逻辑门：与、或、非。
4. 布尔代数：逻辑表达式，真值表，逻辑运算的常用运算律。

5. n-2^n变量译码器，如“3-8译码器”等。
6. 不同位宽的数据选择器，如“1位宽4选1”、“8位宽32选1”等。
7. 一位全加器，串行进位多位全加器。
[串行进位4位加法器](https://blog.csdn.net/qq_41982581/article/details/82661883?utm_medium=distribute.pc_relevant_download.none-task-blog-2~default~BlogCommendFromBaidu~default-1.nonecase&dist_request_id=1328769.69202.16176746047322469&depth_1-utm_source=distribute.pc_relevant_download.none-task-blog-2~default~BlogCommendFromBaidu~default-1.nonecas)
锁存器与触发器。
8. 触发器时序分析，触发器的Setup延迟、Hold延迟和Clock-to-Q延迟的含义及原理
9. 典型状态机设计。
10. 计数器设计，如二进制计数器、模-n计数器。
11. 移位寄存器设计。

****
配合以上基础知识，给出对应的器件verilog实现。

其中包括：
* 01.verilog模块声明与调用
* 02.bit逻辑运算
* 03.n-2^n变量译码器实现
* 04.2^n-n变量编码器
* 05.多路选择器
* 06.多路选择器（1-hot）
* 07.全加器
* 12.普通D触发器
* 13.带使能的D触发器
* 14.带使能和重置的D触发器
* 15.32个32位寄存器堆



