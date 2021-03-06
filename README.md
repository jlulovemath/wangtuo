---
title: wangtuo_downloader.exe
---



<h1 align="center">基于Python的电子书一键下载程序</h1>

## 程序简介

1. 程序名称：wangtuo_downloader.exe
2. 程序大小：5.62MB

## 下载方式

1. GitHub直接下载
2. 通过如下链接下载：http://jlu.wangtuo.co/wangtuo_downloader/wangtuo_downloader.exe

## 版本

version1.0

## 运行环境与条件

1. 一个有D盘或者C盘的电脑
2. 如果全部下载则至少拥有4GB剩余内存空间
3. 连网且下载过程需要保证网络畅通
4. 我希望该应用程序可用的时候可用
5. 注：该应用程序的运行无须Python环境，直接运行即可

## 基本原理

1. 基于Python爬虫爬取相应文件
2. 基于pyinstaller封装称为exe应用程序

## 保护机制

1. 该应用程序会最先下载一个wangtuolibrary.html文件，作为连接的请求文件，该文件是我的网站的重定向文件，打开该文件可直接跳转到我的网站
2. 如果我在远程仓库删除该文件，应用程序将会失效，显示连接失败，没有下载权限

## 功能简介

1. 用于下载数学专业的电子书籍，会下载到D盘下wnagtuo_downloader文件夹
2. 一键全部下载或者分类别快速下载
3. 无须Python环境依赖
4. 整体下载速度较快
   - 一键全部下载大概需要25分钟左右，文件总大小3.02GB

## 温馨提示

<font color="red">请严格按照输入要求进行输入，否则两次不按照要求输入会关机！</font>

相关代码

```python
# 计算非法输入次数
mistake = 0
# 定义关机函数
def shutdown() :
    global mistake
    if mistake >= 2 :
        print('你已经多次进行非法输入,你的电脑将马上关机')
        os.system('shutdown /s /t 3')
```

## 说明

1. 本人担保应用程序的安全性，除去不按照要求输入会关机外，无其他特殊功能，可放心食用
2. 该程序全程由吉林大学数学学院王拓，转载请注明出处

## 当前版本可下载内容目录

主要包括如下九类：

1. 期末考试往年题（吉林大学）

   - 数学分析II

   - 高等代数II

   - C语言

   - 抽象代数

   - 复变函数

   - 概率论与数理统计

   - 普通物理II

   - 微分几何

   - 实变函数

   - 科学计算方法

   - PDE

   - 泛函分析

   - 集合论

   - 微分动力系统

   - 最优控制基础

   - 数学模型

   - 非线性规划

   - 计算数学专业课

2. 分析与微分方程
   - 数学分析
   - 复变函数
   - 实变函数
   - 泛函分析
   - Fourier分析
   - 调和分析
   - ODE
   - PDE

3. 代数与数论
   - 高等代数
   - 抽象代数
   - 代数学进阶
   - 数论

4. 概率与统计
   - 概率论与数理统计
   - 数理统计

5. 几何与拓扑
   - 空间解析几何
   - 拓扑学
   - 微分几何

6. 技术与编程
   - Python
   - LaTeX
   - 人工智能

7. 计算数学
   - 数值分析

8. 应用数学
   - 数学建模

9. 其他
   - 物理

