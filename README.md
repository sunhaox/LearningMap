
# Learning Map

学习心得地图，欢迎补充。  
:computer: 教程（网页）  
:notebook: 教程（文件）  
:tv: 教程（视频）
:gift: 例程  

## 目录  
  
3D_ToF

* [原理](###原理 '标题')
* [标定](###标定 '标定')

C/C++  

* [Qt](###Qt 'Qt')  
* [OpenCV](###OpenCV 'OpenCV')  
* [PCL](###PCL 'PCL')  

Embedded

* [STM32](###STM32 'STM32')
* [FPGA](###FPGA 'FPGA')

Python  

* [基础](###基础 '基础')
* [Tensorflow](###Tensorflow 'Tensorflow')

## 3D ToF

### 原理

:computer: [ToF深度相机原理](http://sunhx.cn/a/tuxiang/2019/0421/51.html 'ToF深度相机原理')  

:gift: [相机tcp通信demo](https://github.com/dongmuliu/Tof-TCP-socket-demo '相机tcp通信demo')

:gift: [相机udp通信demo](https://github.com/dongmuliu/Tof-UDP-Socket-Demo '相机udp通信demo')

### 标定

:computer: [相机的畸变矫正](http://sunhx.cn/a/tuxiang/2019/0420/48.html '相机的畸变矫正')

:computer: [相机标定原理及其Matlab步骤](http://sunhx.cn/a/tuxiang/2019/0617/64.html '相机标定原理及其Matlab步骤')

### 点云

:computer: [深度相机坐标系变换](http://sunhx.cn/a/tuxiang/2019/0420/49.html '深度相机坐标系变换')  

:computer: [深度图像转换点云](http://sunhx.cn/a/tuxiang/2019/0420/50.html '深度图像转换点云')

:gift: [深度、点云图像的实时显示](https://github.com/dongmuliu/SmartEye '深度、点云图像的实时显示')  
（上位机软件详细代码讲解）

## C/C++

### Qt

:computer: [VS2015+Qt环境搭建](http://sunhx.cn/a/chengxu/2016/0410/22.html 'VS2015+Qt环境搭建')  

:computer: [Qt(Windows) Debugger设置](http://sunhx.cn/a/chengxu/2017/0119/31.html 'Qt(Windows) Debugger设置')

:tv: [丁林松QT高级编程视频教程](http://www.icoolxue.com/album/show/282 '丁林松QT高级编程视频教程')  
（至少学完前20讲）  

### OpenCV

:gift: [文件转换助手](https://github.com/dongmuliu/SmartEye '文件转换助手')  
(csv、bin、png读取与显示详细代码讲解)

### PCL

:computer: [windows系统下配置PCL1.8.0和VS2013](https://blog.csdn.net/wokaowokaowokao12345/article/details/47361369 'windows系统下配置PCL1.8.0和VS2013')

:gift: [PCL学习例程](https://github.com/HadenSun/PCLTest 'PCL学习例程')  
（PPT教程讲解，附带详细代码实现）

:gift: [CloudViewer](https://github.com/dongmuliu/CloudViewer 'CloudViewer')  
（基于Qt和PCL的点云可视化工具）

:gift: [PointCloudTools](https://github.com/HadenSun/PointCloudTools 'PointCloudTools')  
（基于Qt和PCL的点云处理工具）

## Embedded

### STM32

推荐购买正点原子开发板，附送配套教程。  
单片机开发需要熟练掌握C语言，了解硬件电路。  
通用IO -> 按键输入 -> 串口通信 -> 外部中断 -> 定时器中断 -> PWM输出  
（ADC、DAC转换和I2C、CAN通信建议掌握）  

### FPGA

根据需要，使用ZYNQ7020芯片。ZYNQ-7000系列是基于ARM Cortex-A9内核处理器和FPGA结构的SoC家族。  
学习建议掌握一定Linux编程基础。

:notebook: [夏宇闻-Verilog经典教程](http://bbs.elecfans.com/jishu_904799_1_6.html '夏宇闻-Verilog经典教程')  
（基本Verilog语法和思路讲解，重点第三、四、五章）

:notebook: [ALINX_ZYNQ(AX7021)开发平台基础教程](https://github.com/HadenSun/LearningMap/blob/master/FPGA/cource_s1_ALINX_ZYNQ(AX7021)%E5%BC%80%E5%8F%91%E5%B9%B3%E5%8F%B0%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8BV1.01.pdf 'ALINX_ZYNQ(AX7021)开发平台基础教程')  
（推荐AX7021开发板作为入门开发板，熟悉FPGA基本语法及编程、下载、调试步骤，熟悉ARM裸板程序编程流程，熟悉Linux编译使用）

:notebook: [MYC_C7Z01020入门指导手册](https://github.com/HadenSun/LearningMap/blob/master/FPGA/MYC_C7Z01020%E5%85%A5%E9%97%A8%E6%8C%87%E5%AF%BC%E6%89%8B%E5%86%8C.pdf 'MYC_C7Z01020入门指导手册')  
（实际开发使用了MYC_C7Z020核心板，这里主要关心PS端网络使用）

## Python

### 基础

:tv: [零基础入门Python](https://www.bilibili.com/video/av4050443?from=search&seid=2515798939366199627 '零基础入门python')  
（教程比较细致，适合于没有编程基础的学习）  
  
:notebook: [简明Python教程](http://www.kuqin.com/abyteofpython_cn/ '简明Python教程')  
（简单基础，侧重对比不同语言区别，推荐已经有编程思想的）  
  
### Tensorflow

:tv: [深度学习框架Tensorflow学习与应用](https://www.bilibili.com/video/av20542427?from=search&seid=5043446637980668181 '深度学习框架Tensorflow学习与应用')  
（实战训练，没有做基础知识讲解）
