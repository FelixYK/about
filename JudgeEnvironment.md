# 大项目评测环境

[TOC]

## 编译器服务器配置

CPU: Intel Xeon E5-2640 2.5GHzz * 1 (in VMWare)

Memory: 32.00 GB

OS: Windows 10 Pro x64

| 编译器 ID | 名称 | IDE | IDE 模式 | 命令行参数 |
|-------------|---------------|----------|----------|--------------|
| gcc51c11    | TDM-GCC 5.1.0 | -- | -- | `gcc -O2 -s -Wall -o foo.exe foo.c -lm -Wl,--stack=134217728 -std=c11 -m32` |

## 对局服务器配置

CPU: Intel Xeon E5-2640 2.5GHzz * 1 (in VMWare)

Memory: 32.00 GB

OS: Windows 10 Pro x64

