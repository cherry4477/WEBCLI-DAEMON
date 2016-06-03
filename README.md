##1通信机制
###1.1 DataHub WEB的通信机制
DataHub web ，通过用户名、密码登录DataHub server。
###1.2 WEB CLI的通信机制   
有两次登录过程。  
* 首先，用户启动WEB CLI时，用户登录Daemon，此过程由系统自动帮用户完成，用户感知不到。  
* 第二步，用户成功登录Daemon后若有需要访问SERVER的操作，则WEB  CLI向Daemon发送登录Server指令。

###1.3 业务流程图
![image](https://github.com/asiainfoLDP/WEBCLI-DAEMON/blob/master/tongxinjizhi.jpg)