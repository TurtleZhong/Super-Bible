# SLAM基础问题

### 问题列表
*   [1.欧式变换，相似变换，仿射变换，射影变换的区别？](#1)
*   [2.Homograph 和 Fundamental Matrix 以及Essential Matrix 的区别，有几个自由度，为什么有这么多自由度，如何计算？](#2)
    *   [2.1 Essential Matrix 原理与推导](#2.1)
    *   [2.2 Essential Matrix 计算方法](#2.2)
    *   [2.3 Homograph Matrix](#2.3)
*   [3.视差与深度的关系?(双目视觉)](#3)

### <a name = "1">1.欧式变换，相似变换，仿射变换，射影变换的区别？</span>

**欧式变换**
首先**欧式变换**是将刚体在三维环境中原封不动的进行旋转或者平移。

**相似变换**, **仿射变换**, **射影变换**
![](images/Q1.jpg)

### <a name = "2">2.Homograph 和 Fundamental Matrix 以及Essential Matrix 的区别，有几个自由度，为什么有这么多自由度，如何计算？</span>

#### <a name = "2.1">Essential Matrix 原理与推导：</span>
![](images/Q2_1.jpg)


#### <a name = "2.2">Essential Matrix 计算方法：</span>
![](images/Q2_2.jpg)

#### <a name = "2.3">Homograph Matrix</span>

### <a name ="3">3.视差与深度的关系?(双目视觉)</span>
d = f*b/z

