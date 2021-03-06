# 一些PhotoShop算法破解

- PS色调均化滤镜算法.cpp 实现了PS中的色调均化滤镜，原理请看：https://www.cnblogs.com/Imageshop/p/3139209.html
- PS高反差保留算法.cpp 实现了PS中的高反差保留，原理就是原图-高斯滤波图像+127,可以自己控制滤波半径来得到不同程度的细节保留。
- PS马赛克算法.cpp 实现了PS中的马赛克算法，原理就是让图像中的所有像素成块状，而每个块的颜色则取决于块内像素的平均值或块内像素的随机值。
- PS挤压特效算法.cpp 实现了PS中的挤压特效，原理是通过数学极坐标的形式，将当前像素、图像中心店和过中心点的水平线这三要素画出的一个极坐标，然后根据指定的挤压度，在当前点与中心点所连的直线上映射出一个像素点，此像素点即为目标像素点。
- PS 色彩特效.cpp 实现了PS中的一些色彩特效算法如：碧绿效果，老照片效果，冰冻效果，熔铸效果，暗调效果，对调效果。
- PS连环画算法.cpp 实现PS中的连环画特效，效果没有使用PS软件好，使用PS制作连环画的教程可以看：http://blog.sina.com.cn/s/blog_54fc25ad0100rb6n.html
- PS剪纸艺术滤镜算法.cpp 实现了PS中的剪纸艺术滤镜，可以将剪纸变换另外一种风格，比如红色的龙变成黄色龙。
- PS 灰色浮雕算法.cpp 实现了PS中的灰色浮雕滤镜，对模板个元素进行三级运算处理，然后进行卷积运算，最后将图像灰度化。我实现的过程核这个不太一致，是先灰度化了再处理，最好是将灰度化放到最后一步。
- PS八方向浮雕算法.cpp 实现了PS中的八方向浮雕滤镜。
- PS调和浮雕算法.cpp 实现了PS中的调和浮雕滤镜。
- PS钝化蒙版算法.cpp 实现了PS钝化蒙版算法，先根据用户指定的钝化度对图像进行高斯模糊处理，再对高斯模糊处理结果与原图像进行钝化处理。 钝化度用来改变像素间的对比度强弱，钝化度，取值（0~100），钝化值越小，钝化的部分就越窄，仅仅会影响边缘像素； 钝化值越大，钝化的范围越宽，效果更明显。
- PS拉普拉斯锐化算法.cpp 实现了PS拉普拉斯锐化算法，原理请看：https://blog.csdn.net/just_sort/article/details/93870203
- PS自由锐化算法.cpp 实现了PS自由锐化算法，原理请看：https://blog.csdn.net/just_sort/article/details/93870203
- PS模糊滤镜之平滑算法.cpp 实现了模糊滤镜之平滑算法，原理请看：https://blog.csdn.net/just_sort/article/details/93876313
- PS模糊滤镜之中值模糊.cpp 实现了模糊滤镜之中值模糊算法，原理请看：https://blog.csdn.net/just_sort/article/details/93876313
- PS模糊滤镜之高斯模糊.cpp 实现了模糊滤镜之高斯模糊算法，原理请看：https://blog.csdn.net/just_sort/article/details/93876313
- PS模糊滤镜之运动模糊.cpp 实现了模糊滤镜之运动模糊算法，原理请看：https://blog.csdn.net/just_sort/article/details/93876313
- PS模糊滤镜之径向模糊算法.cpp 实现了模糊滤镜之径向模糊算法，原理请看：https://blog.csdn.net/just_sort/article/details/93876313
- PS图像错切算法.cpp 实现了图像错切算法，可以以一定的角度在水平或垂直方向进行错切。
- PS图像缩放算法.cpp 实现了图像缩放算法，采用最邻近插值的方式，实现图像的放大缩小。
- PS图像转置算法.cpp 实现了图像转置算法，长宽互换，下标转置即可。
- PS镜像翻转算法.cpp 实现了图像的镜像翻转算法，分为水平和垂直两个方向。
- PS图像平移算法.cpp 实现了图像平移算法，且可选图像尺寸保持不变或者放大两种模式。
- PSMinMax运算算法.cpp 实现了MinMax运算，对两张输入大小相同的图片进行逐像素运算合成目标图像。
- PS算术乘法和除法.cpp 实现了对输入的两张图像进行乘法或除法的运算合成新图像。
- PS算术加法和减法.cpp 实现了对输入的两张图像进行加法或减法的运算合成新图像。
- PS色彩均衡化算法.cpp 实现了PS色彩均衡化算法，原理请看：https://blog.csdn.net/just_sort/article/details/94430129
- PS负像算法.cpp 实现了PS负像算法。
- PS亮度调节(曝光不足或过量).cpp 实现了PS中的亮度调整，调整曝光不足和过量。
- PS对比度增强算法.cpp 实现了PS中的对比度增强，根据用户指定的一个对比度，分别与原始R、G、B色彩分量进行一定比例的缩放，从而拉开原色色彩亮度级别的分布，达到对比度增强的作用。
- PS色彩平衡(偏色校正).cpp 根据用户指定的R、G、B三个色彩的调整分量，分别附加到对应的色彩分量上，从而改变原始图像的色彩。
- PS图像素描算法.cpp 原理就是图像去色后转置，然后接高斯滤波，最后对去色的图和模糊的图进行图层混合。
- PS模糊滤镜之表面模糊算法.cpp 其作用是在保留图像边缘的情况下，对图像的表面进行模糊处理，效果比双边滤波好。
- PS模糊滤镜之水波效果算法.cpp 这个算法原理不清楚，最先出处是这个博客：https://blog.csdn.net/matrix_space/article/details/42396829 。但他也没说明原理，还需研究下。
- PS模糊滤镜之波浪特效.cpp 和水波效果一样，使用坐标变换实现。
- PS二维高斯蒙版算法.cpp 实现了二维高斯蒙版算法，原理请看：https://chenjunkai.blog.csdn.net/article/details/57942262
- PS图像色调分离算法.cpp 实现了色调分离算法，原理就是将R, G, B每个通道 0-255 的色调区间进行强制划分到给定的区间里去，所以色调会合并，最终的图像看起来颜色就是一块一块的。
- PS模糊滤镜之融化效果.cpp 原理是使用了非线性滤波，在窗口中取所有像素的最小值赋值给窗口中心像素点。

