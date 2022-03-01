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
