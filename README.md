# packetBuilder
> 这是一个数据包生成器。你可以参悟这部分代码构建任何协议的数据包。
即将更新

## 概述
```
几年前为了验证之前学的TCP/IP原理，CCNP(思科高级网络工程师)相关底层知识而写的一个C语言开发的工具。
```

## 缺点
```
代码比较原始，没有抽象封装出来，做成工具，不方便别人直接使用，但绝对是学习互联网底层的好东西。
```

## 优点
```
1、带有大量中文注释。
2、基于原始套接字构造各种常见的和不常见的数据包，包括TCP, UDP, HTTP, DNS, ARP等数据包。
3、支持任意报头字段设置。
4、支持负载内容自定义。
```

## 特色
```
这个工程很就久没更新了，也没有计划开发成一个可以高度复用的数据包生成器。
但是依然有足够的参考价值：
1、你可以学到简单的Linux C语言的项目工程的编码构建方式
2、你可以参照这些代码构造任意结构的数据包。
3、你可以通过这些代码学习互联网底层深处的细节。
4、你可以通过它知道网络安全或者黑客攻击手段的原理。
5、你可以结合协议分析工具观察到互联网络通信的本质。
```
