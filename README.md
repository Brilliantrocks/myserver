# myserver
用于网络编程实践的轻量级web访问服务器
* 使用静态线程池避免了动态生成线程造成的性能下降。
* 使用非阻塞socket和epoll实现io复用，Proactor模型的并发事务处理。
* 使用有限状态机模型解析http报文，编写cgi接口支持解析GET和POST方式的报文
* 使用mysql数据库储存用户密码数据，实现了注册登陆功能，以便获得服务器端图片视频等数据。
* 使用同步/异步日志记录服务器的运行状态。
服务器框架：
<div align=center><img src="https://www.hualigs.cn/image/6061eb624735b.jpg"/> </div>
