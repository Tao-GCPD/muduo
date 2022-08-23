# muduo network library
# 简介
- muduo是一个基于Reactor模型的现代Ｃ++ 网络库，它采用非阻塞 IO 模型，基于事件驱动和回调，原生支持多核线程，适合编写Linux服务器多线程网络应用程序。

> 原作者gihub[https://github.com/chenshuo/muduo](https://github.com/chenshuo/muduo)
- 本项目在保留原有功能和特性上，移除boost库依赖，大量使用C++11新特性，支持跨平台操作。
> 项目编译执行`./autobuild.sh`,测试用例进入`example`文件夹，`make`生成服务器测试用例。
