Hypertext Transfer Protocol -- HTTP/1.1
=======================================

>原文地址： [http://tools.ietf.org/rfc/rfc2616.txt][1]

# 文档状态

本文档规定了用于在互联网社区中进行通信的互联网标准跟踪协议（Internet Standards track proto），以及用于改进的讨论意见。有关标准化状态和协议状态的内容，请参见"因特网官方协议标准（Internet Official Protocol Standards, STD 1)"中当前版本的相关信息。本文档对发行方式无限制。

# 版权声明

   Copyright (C) The Internet Society (1999).  All Rights Reserved.

# 摘要

HTTP协议是一种应用层协议，可应用于分布式/协作/超媒体信息系统。协议本身是通用、无状态的，通过对其请求方法/错误码/请求头进行扩展，HTTP协议的适用范围可扩展到超文本之外，例如应用于域名服务器和分布式对象管理系统等（参见[ref-47][2]）。HTTP协议的特点之一就是数据表示的可协商性，即允许系统的构建和数据的传输时相对独立的。

自1990年起，HTTP协议就已应用于万维网。本规范定义的协议专指"**HTTP/1.1**"，是对[RFC-2068][3]的升级。



[1]:    http://tools.ietf.org/rfc/rfc2616.txt
[2]:    ./17.md#ref47
[3]:    http://tools.ietf.org/html/rfc2068