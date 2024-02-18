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



## english article


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




## Mac's computer window cannot pop up

```java
Reference website


https://blog.csdn.net/qq_35664104/article/details/121480884#:~:text=%E6%A0%B9%E6%8D%AE%E6%96%87%E6%A1%A3%E6%89%80%E8%AF%B4%EF%BC%8C%E7%94%B1%E4%BA%8ESDK%E7%89%88%E6%9C%AC%E9%80%A0%E6%88%90%E7%9A%84qmake%E9%97%AE%E9%A2%98%EF%BC%8C%E5%8F%AF%E4%BB%A5%E5%9C%A8pro%E6%96%87%E4%BB%B6%20%E5%A4%B4%E9%83%A8%20%E4%B8%AD%E5%8A%A0%E5%85%A5%E5%A6%82%E4%B8%8B%E8%BF%99%E6%9D%A1%E8%AF%AD%E5%8F%A5%EF%BC%8C%E5%BC%BA%E5%88%B6%E4%BD%BF%E7%94%A8%E4%BD%8E%E7%89%88%E6%9C%AC%E7%9A%84SDK%20QMAKE_MACOSX_DEPLOYMENT_TARGET%20%3D,10.15%201%20%E5%86%8D%E5%9C%A8config%E5%90%8E%E5%8A%A0%E4%B8%8A%E5%BF%BD%E7%95%A5%E7%89%88%E6%9C%AC%E6%A3%80%E6%B5%8B%20CONFIG%20%2B%3D%20sdk_no_version_check

```