# <center>http</center>
 
 我们把互联网想象成客户端和服务端信息的交互。
其过程大致为：

1. 客户端通过浏览器向服务器发送请求（ip地址，子网掩码，网关，域名解析等）
2. 服务器处理请求然后将客户端请求的信息发送给浏览器
3. 浏览器对web服务器发布回来的内容进行渲染修饰，呈现在客户端，从而客户可以看到。

那么，http（超文本传输协议）指的就应该是在上面传输过程中两者所通用的规范要求，能够让服务器懂得客户端在干什么，也能让客户端懂得服务器在干什么。