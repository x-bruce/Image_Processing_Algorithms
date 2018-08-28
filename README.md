# Image Algorithms
- 借助opencv的Mat的数据结构来读取图像，实现一些常见的常见的图像处理算法。

## Image_Canny (C++): 
- Canny边缘检测： [原理参考链接](https://blog.csdn.net/jia20003/article/details/41173767)

## Image_Resize (C++):
- 图像缩放
- nearest（最邻近插值）：[原理参考链接](https://www.cnblogs.com/korbin/p/5612427.html)
- linear（线性插值）：[原理参考链接](https://www.cnblogs.com/korbin/p/5612427.html)
- bicubic（双三次插值）：[原理参考链接](https://blog.csdn.net/u010979495/article/details/78428898)

## Image_Rotate(Python):
- 图像旋转：[原理参考链接](https://blog.csdn.net/linshanxian/article/details/68944748)

## Image_Histogram_Equalization(Python):
- 直方图均衡化：[原理参考链接](https://www.cnblogs.com/tianyalu/p/5687782.html)

## Image_MER(Python):
- 求目标最小外接矩形
- 求凸包（Graham扫描法）：[原理参考链接](https://www.cnblogs.com/Booble/archive/2011/03/10/1980089.html)
- 旋转卡壳法：[原理参考链接](https://blog.csdn.net/hanchengxi/article/details/8639476)

### ##程序没有进行单元测试，仅把公式简单的实现##
### ##临界条件可能报错，仅供参考##