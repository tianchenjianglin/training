# 选拔赛2翻译
## E 2-variable Function
问题陈述
给定整数n，找出满足以下所有条件的最小整数X。
·X 大于或等于N。
·存在一对非负整数（a，B），使得X=a³+a²b+ab²+b³。
约束
·N 是一个整数。
· 0≤N≤10¹ ⁸
输入：
输入来自标准输入，格式如下:
N
输出：
将答案打印为整数。

样本1
输入 9 
输出 15
对于满足9≤x≤14的任意整数X，不存在满足陈述中条件的（a，B）。
当X=15时，（a，B）=（2，1）满足条件。

样本 2
输入 0
输出 0
N 它本身可能满足条件。

样本 3
输入 999999999989449206
输出 1000000000000000000
输入和输出可能不适合32位整数类型。
# 规划
## 好好学习