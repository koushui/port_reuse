## `windows` ：使用方法 

help ： ```port_reuse.exe  port_reuse.exe```


port_reuse.exe [lhost] [reuse prot] [rhost] [rport] [md5(myip)]

默认两分钟关闭端口复用，如有需要自行修改。（长连接的请求，关闭端口复用以后不影响当前建立的长连接）

其中myip为指定一个访问他端口的IP,只有通过这个IP访问才会跳转复用端口，否则访问还是原来的业务。

不依赖防火墙，注意使用管理员权限执行

![image-20240105103740579](image-20240105103740579.png)

![image-20240105104424386](image-20240105104424386.png)



## `linux` ：使用方法 

help ： ```./port_reuse_linux ./port_reuse_linux```

请自行测试那些端口可以复用

**仅供技术研究使用，请勿用于非法用途，否则后果作者概不负责**
