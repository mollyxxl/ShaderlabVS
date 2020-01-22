ShaderlabVS
===========
mod by mollyxxl
* Visual Studio 2019
* 增加支持Unity宏定义、函数
* 修复部分bug
--------------
------------------------------------------


ShaderlabVS 用于 Unity Shaderlab 编程的 Visual Studio 插件。最新的版本可以从 [这里](http://blog.shuiguzi.com/2014/10/28/Release/) 或者 Release 页面下载。

如果你在找支持 Visual Stuido Code 的 Shaderlab 插件，可以看下 [ShaderlabVSCode(Free)](https://marketplace.visualstudio.com/items?itemName=amlovey.shaderlabvscodefree#overview) 这个插件

[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/wudixiaop/ShaderlabVS/) [![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=0.8&x2=0)](http://blog.shuiguzi.com/2014/10/28/Release/)

### 支持的文件:

* .shader
* .cginc
* .glslinc
* .compute
* .cg
* .hlsl

Features
-----

### 代码高亮和大纲

![Highlighting](./img/Highlighting.PNG)

### 帮助信息

![QuickInfo](./img/QuickInfo.PNG)

### 代码自动完成

![CodeCompletion](./img/CodeCompletion.PNG)

### CG 以及 Unity 函数提示

![SignatureHelp](./img/SignatureHelp.PNG)

### 支持黑色主题

![dark](./img/dark.png)

开发
-----

### 环境需求

* Visual Studio
* Visual Studio SDK

### 如何在 Visual Studio 中调试
1. 下载和安装 Visual Studio SDK (VS 2013 之前需要这一步)
2. 打开 ShaderlabVS 解决方案 
3. 按 *F6* 编译整个方案
4. 请确 Shaderlab 项目设置中的 **Debug** 标签页下的 **_Start exteral program_** 和 **_Comand line arguments_** 项设置的值如下:
    1. 将 **_Start exteral program_** 设置为 devenv.exe 的路径 (Visual studio 主程序)
    2. 将 **_Comand line arguments_** 设置为 **/rootsuffix Exp**. 下图是设置的实例:

![](./img/DebugSettings.PNG)

### 支持的 Visual Studio 版本:
* Visual Studio 2013
* Visual Studio 2015
* Visual Studio 2017

__其他版本暂时没有测试，欢迎 Pull Request 添加测试结果.__

### 感谢

