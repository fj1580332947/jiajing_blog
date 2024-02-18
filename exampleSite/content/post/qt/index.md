+++
author = "coucou"
title = "日记"
date = "2024-02-18"
description = "日报专题之20240204"
categories = [
    "qt"
]
tags = [
    "qt"
]
image = "/assets/img/1.jpg"
+++

<!-- ![](1.jpg) -->

# February 18th, 2024  Sunday, Sunny



### english article


> 1. The **Catalan** government in the northeast of Spain has **declared** a state of emergency in response to a record-breaking **drought**.

```java


QApplication: No such file or directory 完美解决方案
之后提示出错： fatal error: QApplication: No such file or directory 由于Qt5将大部分桌面部件移到了Qt Widgets模块中，即QApplication已经从原来的<QtGui/QApplication>移动到<QtWidgets/QApplication>了。从下图也可以看出来。

 

 

 

所以为解决找不到QApplication文件 这个问题，有两种方法：

 

法1：
 

#include <QtWidgets/QApplication>
#include <QtWidgets/QPushButton>
 

法2：也可以保持原代码不变，即保持
 

#include <QApplication>
#include <QPushButton>

而在.pro文件中添加

greaterThan(QT_MAJOR_VERSION, 4): QT += widgets


```









<!-- 
![我的图片](listen.png)
![我的图2](listen2.png) -->