# 组成

一个完整的监控摄像机主要由外壳，红外灯板，主芯片，镜头，IR-CUT切换器，尾线，以及其他的扩展功能部件组成，其中核心是主芯片。

### ![](/assets/摄像机外观图1.jpg)![](/assets/摄像机外观图2.jpg)

### 外壳



### 芯片

不同类型（网络，模拟，数字）的摄像机使用方案，芯片构成有差别，但从整体上看，监控摄像机的芯片核心组成图像处理器（DSP,ISP,SOC）+图像传感器（sensor）。

> DSP,ISP,SOC的区别
>
> ISP 是Image Signal Processor 的简称，也就是图像信号处理器。而DSP是Digital Signal Processor 的缩写，也就是数字信号处理器。
>
> ISP一般用来处理Image Sensor（图像传感器）的输出数据，如做AEC（自动曝光控制）、AGC（自动增益控制）、AWB（自动白平衡）、色彩校正、Lens Shading、Gamma 校正、祛除坏点、Auto Black Level、Auto White Level 等等功能的处理。
>
> 而DSP功能就比较多了，它可以做些拍照以及回显（JPEG的编解码）、录像以及回放（Video 的编解码）、H.264的编解码、还有很多其他方面的处理，总之是处理数字信号了。
>
> SOC,

一般的模拟摄像机的图像处理器我们成为ISP，网络摄像机的图像处理器因为还涉及到编码等过程，我们称之为DSP。

![](/assets/CONTENTS7_C_143.png)模拟摄像机AHD方案 NVP2475H的系统框图\*

\*图片来源：[nextchip官网](http://www.nextchip.com/ch/products/product.asp?hGubun=ISP&seq=143#none)

### ![](/assets/Hi3519 Block Diagram.jpg)

网络摄像机方案Hi3519系统框图\*\*

\*\*图片来源：[海思官网](http://www.hisilicon.com/en/Products/ProductList/Surveillance)

摄像机常见的ISP,DSP处理器方案及品牌

监控摄像机常用的图像处理器（sensor）型号及品牌

### 镜头

镜头的作用是从被摄物体收集光信号到摄像机光电传感器的光敏区， 镜头是由一组透镜和光阑组成的。

光阑\(光圈\)

能进入镜头成像的光束，其大小是由透镜框和其他金属框决定的。 往往这样限制光束还不够,还要在镜头中设置一些带孔的金属薄片来限制光束，称为光阑。

#### 镜头的分类

### 尾线

### IR-CUT

### 红外灯，补光灯

### 扩展功能\(拾音器，外接报警\)



