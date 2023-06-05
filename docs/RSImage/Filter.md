# Day 7. 图像空间域滤波
图像空间域滤波是一种邻域算子，通过对某个像素点一定范围内的邻域点（如：3*3,5*5）作用某种算子，得到一幅新的图像。

根据作用的算子不同，可以分为平滑滤波和边缘增强滤波。平滑滤波顾名思义，就是将图像的细节部分弱化，得到的图像更为模糊，最常用的算子有均值滤波。
边缘增强算子正好相反，是突出图像中的边缘部分，增强细节。

空域滤波的运算过程并不复杂，比如滤波算子是3*3的矩阵，将3*3的窗口在图像的每个像元中滑动（中心对齐某个像元），卷积求和的方法得到新的像素值即为滤波后的图像。
具体细节，参考下列资料。

- [参考资料](https://zhuanlan.zhihu.com/p/50238655)
---
|[Home](Subject.md) |