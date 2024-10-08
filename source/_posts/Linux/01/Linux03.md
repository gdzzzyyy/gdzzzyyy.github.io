---
title: Linux03
date: 2024-08-31 18:32:06
tags:
---
# 重点回顾
- 计算机主要以二进制作为单位，而且目前常用的磁盘容量单位为 B，1 B = 8 bit，其他的以 1024 为其倍数，如 1 GB = 1024 MB
- 操作系统（Operation System）主要用于管理与驱动硬件，因此必须要能够管理内存、管理设备、负责进程管理以及系统调用等。因此，只要能够让硬件准备妥当（Ready）的情况，就是一个很棒的操作系统了
- 操作系统重点仅在于驱动与管理硬件，而要使用硬件时，就得需要通过应用软件或则是 shell 的功能，来调用操作系统操作硬件工作。因此，目前操作系统除了上述功能外，通常已经包含了日常工作所需要的应用软件了
- Unix 的前身是由贝尔实验室的 Ken Thompson 利用汇编语言写成的，后来在 1971~1973 年间由 Dennis Ritchie 以 C 语言进行改写，才成为 liunx
- 1977 年有 Bill Joy 释出 BSD（Berkeley Software Distribution），这些称为 UNIX like 的操作系统
- 1984 年由 Andrew Tannenbaum 制作出 Minix 操作系统，该系统可以提供源码以及软件
- 1984 年由 Richard Stallman 提倡 GUN 项目，倡导自由软件（Free Software），强调其软件可以自由地取得、复制、修改与再发行，并规范出 GPL 授权模式，任何 GPL（General Public License）软件均不可单纯仅销售起软件，也不可修改软件授权
- 1991 年由芬兰人 Linus Torvalds 开发出 Linux 操作系统，简而言之，Linux 成功的地方主要在于 MInix(Unix)、GUN、Internet、POSIX 以及虚拟团队的产生
- Linux 本身就是个了不起的操作系统，其开发网站设立在 http://www.kernel.org，我们称 Linux 操作系统最底层的数据为 内核（Kernel）
- 目前 Linux 内核的开发分为两种版本，分辨是稳定版本的偶数版，如 2.6.x，适合商业与家用环境使用；一种是开发中版本，如 2.5.x 版，适合开发特殊功能的环境
- Linux Distribution 是 Linux kernel + Free Software + Documentations（Tools）+ 可完全安装的程序 所制成的一套完整的系统。