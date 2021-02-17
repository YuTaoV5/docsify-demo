<!--
 * @Author: ProtoDrive000
 * @Date: 2021-02-17 13:14:30
 * @LastEditTime: 2021-02-17 13:14:31
 * @Description: 
 * @FilePath: \docs\zh-cn\智能车\README.md
 * @Copyright © : 2021年 赛博智能车实验室. All rights reserved. 
-->

# CodeV1.2+细解

![](https://img.shields.io/badge/Code-V1.2-blue)
![](https://img.shields.io/badge/%20-%E5%9B%9B%E8%BD%AE-green)
![](https://img.shields.io/badge/%20-摄像头-green)
![](https://img.shields.io/badge/%20-搜线-green)

***||||||||||||||||||||||||||||||||  Author: ProtoDrive000         ||||||||||||||||||||||||||||||||||||||||***

---
***2019年12月本次`CodeV1.2+`更新：修复0拐点和1拐点条件下的补线***
---
本次`CodeV1.2`运用的是**基于左右搜的笛卡尔坐标系人字寻找拐点体系**


---
**文件列表**
 - Cross_repair
 - IMG.c        `储存图像`
 - IMG.h        
 - basic.cpp    `搜线+找拐点工具`
 - basic.h      
 - output.cpp   `打印输出工具`
 - output.h     
 - tool.cpp     `一般性工具`
 - tool.h       `提供各类结构体接口`
 - rule.h       `图像特征宏定义`
 - head.h       `头文件合集`
 
----------
###基本思路
    相较于CodeV1.0+，我废除了点的方向体系，综合特征后，我打算使用新的搜线工具记录拐点。
拐点算法介绍见https://www.zybuluo.com/ProtoDrive000/note/1684669

`shot`文件夹里面有生图像成数组和数组转图像的小项目，以及学长的上位机

***||||||||||||||||||||||||||||||||  Final interpretation is owned by ProtoDrive000         |||||||||||||||||||||||||||||||||||||||||||***





