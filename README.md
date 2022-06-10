# MyMatlab-二维曲线图
Matlab Explore 
1. 对数系坐标图

**semilogx(x1,y1,choose1, x2,y2,choose 2...)**
  
  **loglog(x1,y1,choose1...)**

![image](https://user-images.githubusercontent.com/81022107/155873215-d14a88de-2b06-4ec1-81a3-121fdb3f2a20.png)

可以绘制在其他坐标系下的二维曲线图

比如： 尝试绘制1/x 的直角线性坐标图和三种对数图像

可以先考虑的点： 确定范围并将 y设置为x的等式
比如 x=0:0.1:1.0
y=1/x;
subplot(2,2,1)
然后进行作图 
这里要注意所有的图形应该都考虑对数坐标图。

![image](https://user-images.githubusercontent.com/81022107/156838497-90f71823-dddf-494e-92c0-3ab305dbeeaa.png)

---


2. 其他坐标系下的二维曲线图
（1） 极坐标图 polar(theta,rho,choose)
其中 theta为极角，rho为极经，choose的内容与plot函数相同

（2）按照极坐标方程绘制心形图

![image](https://user-images.githubusercontent.com/81022107/156839108-72bb7cd3-ec11-45c9-8c91-5eabc51be21f.png)

* *t是0到2pi之间的选择点* *



# 统计图
1. 条形类图形
bar 函数： bar (y,style)
其中，参数y可以作为一种数据，而选项style用于指定的分组排列模式。
比如统计图： 用于对家电商品1月份的销售数据，绘制条形图。

![image](https://user-images.githubusercontent.com/81022107/156941178-d29ef194-3ff6-4c09-baa1-763111f48b1d.png)

可以来绘制分组条形图：
先形成一个矩阵叫做y,然后根据矩阵y对可能的情况进行排列。

![image](https://user-images.githubusercontent.com/81022107/156942440-b6315caa-4a55-4c01-a52e-89162b33806e.png)

bar的常用方式有
1. 条形类图形
2. bar函数： bar(x,y,style),x:横坐标，y：存储数据

根据不同年份，x代表年份，y代表不同组数据。bar为以x分类的y，title为group

![image](https://user-images.githubusercontent.com/81022107/156942587-32b57301-2372-432a-8178-17d55173302f.png)

3.直方图
hist函数： 
hist(y), hist(y,x)
其中，参数y是要统计的数据，x用于指定区间的划分方式
比如来绘制服从高斯分布的直方图

![image](https://user-images.githubusercontent.com/81022107/157329037-5098e918-b4bd-402d-84ee-a7ddd7557f6a.png)






