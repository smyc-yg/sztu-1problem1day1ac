# 新手训练营 - 解题报告模板

## 标题：年-月 题号：题目标题 - 解题报告（发布人）
如：

2020-12 POJ1000：A+B Problem - 解题报告（张三）

## 内容

### 题目大意
计算两个数的和
### 解题思路
考察基本的C语法，POJ这道题不涉及多组数据，直接输出即可。而使用 EOF 判断文件结尾也没有问题。

### 复杂度分析
此题只执行一次加法运算，时间复杂度为 `O(1)`。没有涉及数组操作，空间复杂度也为`O(1)`

### 算法资料
该题目无算法

### 心得体会
重在收获了什么技巧，可以是代码层面的奇技淫巧，可以是思路层面的脑洞大开，能够总结为一种套路，以后遇到哪个题可以套一下试试的东西。 

### 代码
```C++
#include <stdio.h>

int main()
{
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d\n", a + b);
    return 0;
}
```