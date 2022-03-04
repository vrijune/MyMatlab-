# MyMatlab-二维曲线图
Matlab Explore 
(1) 对数坐标图
semilogx(x1,y1,choose1, x2,y2,choose 2...)

loglog(x1,y1,choose1...)

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




# 其他坐标系下的二维曲线图
（1） 极坐标图 polar(theta,rho,choose)
其中 theta为极角，rho为极经，choose的内容与plot函数相同

（2）按照极坐标方程绘制心形图
![image](https://user-images.githubusercontent.com/81022107/156839108-72bb7cd3-ec11-45c9-8c91-5eabc51be21f.png)
t是0到2pi之间的选择点



# MyMatlab-三位曲线
