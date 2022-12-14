# IP （Internet Protocol，网际协议）

-   负责：将数据包发送给最终的目标计算机
-   层次：第三层（网络层）
-   通信类型：点对点

    -   想想：通信链路层的功能是什么？

-   主机、路由器、节点是什么？

## 数据链路

物理层负责物理信号和二进制的转换，数据链路层把 01 序列的集合称为“帧"，传输这样的数据块。数据链路层的协议定义**通过通信媒介互联的各设备之间传输的规范**。

以下是几个概念：

-   段：一个被分割的网络
-   网络拓扑：网络的连接和构成形态，有总线型、环型、星型、网状型等

以下是数据链路技术：

-   MAC 地址
    -   识别数据链路中互连的节点
    -   长 48 比特：一般用十六进制表示 ii
        -   1：单播 0/多播 1
        -   2：全局 0/本地 1
        -   3~24：厂商识别码
        -   25~48：厂商内识别码
-   共享介质型网络
    -   设备之间使用同一个载波信道进行发送和接收，基本采用半双工通信，应当对介质进行访问控制。
    -   争用方式（CSMA，载波监听多路访问）：先到先得占用信道
    -   令牌传递方式：沿着令牌环发送一种叫做“令牌”的特殊报文，只有获得令牌的站才能发送数据。
-   非共享介质网络
    -   每个站直连交换机，交换机负责转发数据帧，采用全双工通信方式
-   MAC 地址转发
    -   以太网交换机是持有多端口的网桥。根据数据链路层每个帧目标 MAC 地址决定从哪个端口发送数据。
    -   转发表（Forwarding Table）：自学原理
    -   > 存储转发：检查帧末尾的 FCS 位再转发
        > 直通转发：得知目标地址后立刻转发，不需要全部接收
-   环路检测
    -

> 半双工：只发送/接收（同轴电缆）
> 全双工：同时发送/接收数据（双绞线电缆/光纤电缆）
