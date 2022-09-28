# 莉鸥文档
<https://github.com/liovr/liovr-doc>

莉鸥VR: 廉价开源 VR 硬件

(liovr: GNU/Linux Inexpensive Open source VR hardware)

----

动机: VR 是小众 (市场占有率低), GNU/Linux 也是小众.
作为小众的平方, VR 设备对 GNU/Linux 的支持奇差.
作为直接被忽略的一部分, 怒而自制 VR 硬件. (2022-09)

Motivation: VR is a minority (low market share), GNU/Linux is also a minority.
As the square of minority (minority multiply minority),
the GNU/Linux support of VR device is very bad.
As a part to be directly ignored, angry to DIY VR hardware.


## 主要特点

+ 硬件:
  主要是 PCVR 套件, 包括 (计划中)
  头戴显示器 (HMD), 定位系统 (3DoF/6DoF), 手柄 (3DoF/6DoF) 等.

+ 廉价:
  采用低成本, 容易制造的硬件设计方案, 以及容易获取的零部件.
  (对穷人友好)

  超低成本的同时, 提供及格的使用体验 (60 分性能).

+ 开源: 相关软硬件全部开源.
  软件发布源代码, 硬件发布设计文档, 3D 模型等.

  同时尽量使用 开源的平台 (比如 GNU/Linux, Android),
  开源的开发工具 (比如 [KiCad](https://www.kicad.org/),
  [FreeCAD](https://www.freecadweb.org/),
  [blender](https://www.blender.org/)),
  开源的软硬件依赖组件等.
  理想目标是全栈开源.

+ 开放标准:
  采用 [OpenXR](https://www.khronos.org/OpenXR/) 开放标准,
  从而可以支持广泛的上层软件应用.

+ 支持 GNU/Linux:
  将 GNU/Linux 平台 (以及 Android) 作为优先支持目标.


## 计划的项目

+ `liovr-1` **莉鸥 1 号**: 手机盒子头戴显示器 3DoF

+ `liovr-1b` **莉鸥 1b**: 3D 打印塑料头盔 (电动车头盔)

+ `liovr-2` **莉鸥 2 号**: 手机手柄 3DoF

+ `liovr-3` **莉鸥 3 号**: 头部定位杆 6DoF

+ `liovr-4` **莉鸥 4 号**: 超声波定位系统 6DoF

+ `liovr-4b` **莉鸥 4b**: 超声波定位系统便携版

+ `liovr-5` **莉鸥 5 号**: 超声波定位手柄 6DoF

+ `liovr-6` **莉鸥 6 号**: 微型显示模块 DP 接口

+ `liovr-7` **莉鸥 7 号**: 可变 PPD 显示模块

+ `liovr-8` **莉鸥 8 号**: 模块化 VR 移动平台 (一体机)

+ `liovr-8b` **莉鸥 8b**: 透视摄像头模块

+ `liovr-9` **莉鸥 9 号**: 眼动追踪+面部表情模块


## LICENSE

[`CC-BY-SA 4.0+`](https://creativecommons.org/licenses/by-sa/4.0/)

本仓库的内容使用 创意共享-署名-相同方式共享 (CC-BY-SA 4.0) 许可证 (LICENSE).
This repository is released under Creative Common (CC-BY-SA 4.0) license.
