# NL-means
降噪算法NL-means的C++实现

原图：
![lena.jpg](https://pic2.zhimg.com/80/v2-d31eaabadaf5a247adb9ba044e2fc1b5_hd.jpg)
经过添加高斯噪点和椒盐早点后的图像，将使用高斯滤波、中值滤波、双边滤波以及论文中的NL-means算法对该图进行降噪处理：


![lena_noise.jpg](https://pic3.zhimg.com/80/v2-a4fde900f260d963d94df779d828d4de_hd.jpg)
output:

RAW: 28.0157

time: 39.0843 ms
gaussian: 28.1887

time: 4.29171 ms
median: 30.6392

time: 13.0715 ms
bilateral: 33.161

time: 543.483 ms
nonlocal: 34.1463

![效果图](https://github.com/GitHberChen/NL-means/blob/master/pic/screenshot.png)



点击：https://zhuanlan.zhihu.com/p/45966784 了解详细情况
