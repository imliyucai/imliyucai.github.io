---
layout:     post
title:      Qt for android 实验一
subtitle:   Qt Bluetooth 应用
date:       2025-10-14
author:     yucailee
header-img: img/the-first.png
catalog: false
tags:
    - 软件技术
---

  Qt for android 是将 Qt 程序放到 android 下运行，主要是在 Qt Creator 里配置好编译器，编译下载到 android 机上就可以了。

  我实验用的是 Qt 5.14.2，这是最后一个官方编译好的 Qt 版本。Qt Creator 用了 4.12.4 版本。

  Qt5 的官方文档，见 [Qt5](https://doc.qt.io/archives/qt-5.14/)。
  
  计划先实验蓝牙通信，这个要用 Qt Bluetooth 模块。Qt 5.7 开始提供了这个模块。为了使用它，在 .pro 文件里要加上 QT += bluetooth。

  在 Qt\Docs\ 目录下有各个模块的帮助文档，在 Qt\Examples\ 目录下有各个模块的一些示例，其中有 bluetooth，可惜没有 ble advertising 的，而我首先要做的就是 scan advertising。

  找到 QLowEnergyAdvertisingData 类和 QLowEnergyAdvertisingParameters 类的说明，见 [QLowEnergyAdvertisingData](https://doc.qt.io/archives/qt-5.14/qlowenergyadvertisingdata.html)，[QLowEnergyAdvertisingParameters](https://doc.qt.io/archives/qt-5.14/qlowenergyadvertisingparameters.html)。



### 1

### 2


