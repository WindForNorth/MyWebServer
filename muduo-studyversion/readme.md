muduo-monster的网路核心库，相比原始muduo使用智能指针管理Timer，避免额外的处理定时器自我注销的情况

使用核心库编写基于PingPong协议的测试程序，在AMD Ryzen 5 4500U处理器，4核心，主频2.38GHz，4GB内存的硬件环境，操作系统为Ubuntu22.4的软件环境下，同时运行客户端和服务端程序，均开启4线程建立10000个连接运行100s测试，粗略计算出平均吞吐量约为下图所示的数据：

![image](https://github.com/WindForNorth/PROJECTS/blob/master/image-20230630083101595.png)
