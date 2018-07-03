# 主芯片

不同类型（网络，模拟，数字）的摄像机使用方案，芯片构成有差别，但从整体上看，监控摄像机的芯片核心组成图像处理器（DSP,ISP,SOC）+图像传感器（sensor）。

### DSP/ISP/SOC

> DSP,ISP,SOC的区别
>
> ISP 是Image Signal Processor 的简称，也就是图像信号处理器。而DSP是Digital Signal Processor 的缩写，也就是数字信号处理器。
>
> ISP一般用来处理Image Sensor（图像传感器）的输出数据，如做AEC（自动曝光控制）、AGC（自动增益控制）、AWB（自动白平衡）、色彩校正、Lens Shading、Gamma 校正、祛除坏点、Auto Black Level、Auto White Level 等等功能的处理。
>
> 而DSP功能就比较多了，它可以做些拍照以及回显（JPEG的编解码）、录像以及回放（Video 的编解码）、H.264的编解码、还有很多其他方面的处理，总之是处理数字信号了。
>
> SOC,

一般的模拟摄像机的图像处理器我们称为ISP，网络摄像机的图像处理器因为还涉及到编码等过程，我们称之为DSP。

![](/assets/CONTENTS7_C_143.png)模拟摄像机AHD方案 NVP2475H的系统框图\*

\*图片来源：[nextchip官网](http://www.nextchip.com/ch/products/product.asp?hGubun=ISP&seq=143#none)

![](/assets/Hi3519 Block Diagram.jpg)

网络摄像机方案Hi3519系统框图\*\*

\*\*图片来源：[海思官网](http://www.hisilicon.com/en/Products/ProductList/Surveillance)

##### DSP发展历程

根据不同的摄像机方案应用，DSP经历了从传统模拟标清到现在支持AI，鱼眼矫正，4K/8K高清的发展历程标清时代。

* 模拟标清：模拟标清处理器当时主要被日本SONY，SHARP，韩国的三星等厂家垄断。处理器的能力有限，支持的清晰度按照电视线（TVLine）标识，420线，480线，540线到比较高的



* 网络标清
* 数字高清\(SDI\)
* 模拟高清
* 网络高清
* 消费类产品
* AI,人工智能



> 摄像机常见的ISP,DSP处理器方案及品牌
>
> [https://ipc.name/soc/](https://ipc.name/soc/)

### Sensor

> 监控摄像机常用的图像处理器（sensor）型号及品牌
>
> [https://ipc.name/sensor/](https://ipc.name/sensor/)



