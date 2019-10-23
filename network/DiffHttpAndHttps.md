# 请简述 Http 与 Https 的区别？
## 基本概念
### HTTP
超文本传输协议(HyperText Transfer Protocol)，是目前互联网上应用最为广泛的一种网络传输协议，所有的WWW文件都必须遵守这个标准.   
是一个客户端和服务端请求和应答的标准(TCP)
### HTTPS
完全套接字层超文本传输协议(Hyper Text Transfer Protocol over Secure Socket Layer)或超文本传输安全协议(Hypertext Transfer Protocol Secure).  
就是 HTTP 的安全版，在 HTTP 下载加入 SSL 层，HTTPS 的安全基础是 SSL，所以加密的详细内容就需要SSL

## 区别
| 名称 | HTTP | HTTPS|
| :--- | :---- | :---- | 
|URL|http 开头| https 开头|
|证书|不需要证书| 需要到ca申请证书，<br/> 一般免费证书很少，所以需要一定费用|
|安全|信息明文传输|具有安全性的ssl加密传输协议|
|端口|默认端口80|默认端口443|
|连接|无状态|由SSL+http协议构建的可进行加密传输、身份认证的网络协议<br/>所以首次建立连接会慢一些，但是比http协议安全|
|握手协议|三次握手|如下图|

https握手：   
![](images/https_handshake.png)