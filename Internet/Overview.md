# 名词解释
## 计算机网络
计算机是由若干结点和连接这些结点的链路组成的。

## 互联网
网络通过路由器互联起来，构成了一个覆盖更大的计算机网络，称为互联网。

## ISP
ISP 互联网服务提供商 

## 协议
通信协议（英语：Communications Protocol，也称传输协议）在电信中是指在任何物理介质中允许两个或多个在传输系统中的终端之间传播信息的系统标准，也是指计算机通信或網路設備的共同语言。 通信协议定义了通信中的语法学, 语义学和同步规则以及可能存在的错误检测与纠正。通信协议在硬件，软件或两者之间皆可实现

# 因特网两大组成部分
分为两大部分，边缘部分，核心部分。
## 边缘部分
由各主机构成，用户直接进行信息处理和信息共享，低速连入核心网。
## 核心部分
由路由器连网，负责为边缘部分提供高速远程分组交换。

# 连接方式
连接方式有两种，客户服务器工作方式，对等连接方式。
## 客户服务器工作方式
涉及客户进程，服务进程
## 对等连接方式
为P2P连接方式，进行对等连接方式。本质仍然是客户-服务器方式，对等连接的每一台主机既是客户机，又是服务器。

# 分组交换
采用存储转发技术，把一个报文划分为几个分组再进行传送。
把发送的整块数据称为一个报文，发送报文前把较长的报文划分一个个更小的等长的数据段，加上控制信息组成的首部构成分组，分组又称为包，然后进行分组传送

# 路由器存储转发
以太网交换机的控制器，先把输入端口到来的数据包缓存起来，然后再检查数据包是否正确，然后过滤掉冲突包的错误，确定包正确后，然后取出目的地址，通过查找表找到想要的发送的输出端口的地址，然后该包发送出去。

# 网络常见性能指标
带宽
时延
带宽时延积

# 网络分类
## 扩扑结构
总线型，星形，环形，树形，混合型

## 覆盖面积
广域网，城域网，局域网

# 网络分层的优点
1. 各层之间独立，某一层并不需要知道它下一层是如何实现的，而仅仅需要知道该层通过层间接口所提供的服务。降低问题的复杂度。
2. 灵活性好，任何一层发生变化时，只要层间接口关系保持不变，在这层以上或以下各层都不受影响。此外对某一层提供的服务还可以修改，当某层提供的服务不在需要时，甚至可以取消该层。
3. 结构可以分割开，各层都可以采用合适的技术来实现。
4. 易于实现和维护，庞大复杂的系统被拆分成几个若干相对独立的子系统。
5. 促进标准化工作。

# OSI七层
1. 物理层
2. 数据链路层
3. 网络层
4. 运输层
5. 会话层
6. 表示层
7. 应用层


