---
sort: 2
---
# 基于 LVGL 学习 C 语言 OOP 思想



## LVGL

- [Welcome to the documentation of LVGL!](https://docs.lvgl.io/)
- [欢迎阅读百问网LVGL中文开发手册！](http://lvgl.100ask.org/8.2/index.html)



官网：https://lvgl.io/

github：https://github.com/lvgl/lvgl

手册：https://docs.lvgl.io/master/index.html

中文翻译：http://lvgl.100ask.org/8.2/examples.html

Light and Versatile Graphics Library

轻量级、多功能图形库。

在官网可以看到

这套东西可以运行在16bitCPU上，最低主频16MHz，当然越高越好，ROM最小64KB，RAM最小8KB就能跑。

显存在MCU内部、外部，或在显示控制芯片内都行。

显存分配最小为一行像素，但是1/10最好。

这是个开源项目，遵循MIT协议。

Widgets即部件，有30多个。

显示很灵活，支持各种分辨率屏幕，单色的也可以。

输入也很灵活。

画图也有比较多的功能。

也支持中文文本。


## emWin

emWin属于SEGGER公司下面的一种GUI产品，一种嵌入式GUI解决方案。业界领先的嵌入式图形库，专业的嵌入式GUI。

emWin与单任务和多任务环境兼容，可以使用专有的操作系统，也可以与任何商业RTOS兼容。它以C语言源代码提供，使其成为嵌入式市场的专业、通用GUI，可用于多种不同的场景。

## TouchGFX

TouchGFX属于Draupner Graphics公司的GUI产品，在去年（2018年7月），TouchGFX被ST收购，在STM32上可以免费使用TouchGFX。TouchGFX升级至V4.10，扩展STM32生态系统，并集成在STM32CubeMX中。

## MiniGUI

MiniGUI丰富的功能和可配置性使得它既适用于运行在30MHz CPU的低端设备，也适用于使用GPU的高端设备。为嵌入式和智能物联网设备提供一个成熟的、经过验证的跨平台GUI系统。

就在前不久（2019年9月19日），北京飞漫软件技术有限公司宣布：将在 MiniGUI 4.0.2 版本中支持国产物联网操作系统 RT-Thread！

## Qt



