# eChat

  一个非常简单的C/S型易语言程序，可以实现在同一局域网内聊天，并有传文件功能。

  ![1](https://img-blog.csdnimg.cn/6833b22475c2490c977a942a6472cc4e.png#pic_center)

  ![2](https://img-blog.csdnimg.cn/42e701dbf6d4471db9b91169ce0775f2.png#pic_center)

  ![3](https://img-blog.csdnimg.cn/60e45e82814c44ad867b736e92027458.png#pic_center)
  
  ![4](https://img-blog.csdnimg.cn/3125d7ac970d42a5bdeca3ea1432fb8e.png#pic_center)

## 使用方法

  在某一台电脑上启动服务端，按照要求配置FTP服务器（一般情况下已经配置完成）。
  
  接下来局域网内任意一台电脑都可以启动客户端，将ID、服务器IP填写好（服务器在本机使用127.0.0.1，不在本机使用对应局域网IP）。连接完成后便可开始使用。

## 功能

  服务端具有查看所有活动记录、禁言/取消禁言某人、提醒某人或全体成员、断开某人、向某人或全体成员发信息的功能；

  客户端具有向某人或全体成员发信息、提醒某人或全体成员、向某人传输文件的功能。受禁言时无法使用上述功能。

  说明：传输文件需要保证服务端C盘有足够空间（一般无需担心）、双方都连接上FTP服务器（与负责消息处理的服务端无关），若未能自动连接，请断开与服务端的连接再重连。

## 外部链接

  1. FTP服务器来源 [Slyar FTPserver](https://www.slyar.com/blog/slyar-ftpserver.html)

  2. 设计有所参考 <https://www.bilibili.com/video/av754466413/> ，但是完全重写

  3. 图标来源 Material Design Icons
