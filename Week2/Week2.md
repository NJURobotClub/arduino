# Week2

## 一	任务

- 初步掌握Arduino nano各引脚作用

- 掌握arduino烧录程序步骤

- 熟悉使用面包板

- 利用nano板点亮二极管灯泡

## 二	器材
- LED灯*1
- Arduino Nano 板 *1
- USB-micro数据线*1
- 面板板、排针、杜邦线



## 三	模块介绍

### 1	面包板

#### 介绍

> **面包板**（Breadboard）或叫**免焊万用电路板**（solderless breadboard）是[电子电路设计](https://zh.wikipedia.org/wiki/电子电路设计)中所常用的一种基底。



![breadboard](../pics/breadboard.jpg)

由于板子上有很多小插孔，各种电子元器件可根据需要任意插入或拔出，免去了焊接的工序，节省了电路的组装时间，且元件可以重复使用，非常适合电子电路的组装、调试和训练。

面包板背面有背胶，方便其贴在不同的仪器上。

#### 结构

1. 电源轨

   在面包板的上下两侧分别有两列插孔，一般是作为电源引入的通路。上方第一行标有“+”的一列有5组插孔，每组5个（内部5个孔连通），均为正极。上方第二行标有“-”的一列有5组插孔，每组5个（内部5个孔连通），均为接地。面包板下方第一行与第二行结构同上。如需用到整个面包板，通常将“+”与“+”用导线连接起来，“-”与“-”用导线连接起来。

   ![breadboard-power-slots](../pics/breadboard-power-slots.jpg)

   ![面包板电源轨2](http://www.taichi-maker.com/wp-content/uploads/2017/03/breadboard-power-slots2.jpg)

2.  接线轨

   连接孔分为上下两部分，是我们的主工作区，用来插接原件和跳线。在同一列中的5个插孔（即a-b-c-d-e，f-g-h-i-j）是互相连通的；列和列（即1-30）之间以及凹槽上下部分（即e-f）是不连通的。

   ![breadboard-slots](../pics/breadboard-slots.jpg)

### 2	Arduino Nano

Arduino Nano结构

![nano](../pics/nano.jpg)

我们主要使用Digital Pins



Arduino Nano板需要**电源供电**

有三种方式：

- USB接口：电源电压是稳定的+5V的直流电压。
- 5V Pin：为Arduino开发板供电使用，也可以为外部电子元件提供+5V电源。
- Vin：Vin引脚为Arduino开发板供电时，直流电源电压必须为7V ~ 12V。



#### 四	点亮二极管

引脚连接：

Arduino

| Arduino Nano                | LED等 |
| --------------------------- | ----- |
| 3.3V  / D13(Digital Pin 13) | 长端  |
| GND                         | 短端  |

