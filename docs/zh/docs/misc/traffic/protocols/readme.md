# 协议分析概述

网络协议为计算机网络中进行数据交换而建立的规则、标准或约定的集合。例如，网络中一个微机用户和一个大型主机的操作员进行通信，由于这两个数据终端所用字符集不同，因此操作员所输入的命令彼此不认识。为了能进行通信，规定每个终端都要将各自字符集中的字符先变换为标准字符集的字符后，才进入网络传送，到达目的终端之后，再变换为该终端字符集的字符。当然，对于不相容终端，除了需变换字符集字符外还需转换其他特性，如显示格式、行长、行数、屏幕滚动方式等也需作相应的变换。

相应的，我们在协议分析这一章节中，将会从以下几个方面来介绍这一部分的知识：

- `Wireshark` 常用功能的介绍
- `HTTP` 协议分析
- `HTTPS` 协议分析
- `FTP` 协议分析
- `DNS` 协议分析
- `WIFI` 协议分析
- `USB` 协议分析