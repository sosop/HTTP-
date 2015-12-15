# 一、http基础知识
### 1、http1.0和http1.1支持的方法
![http支持方法](./http-methods.png)
### 2、持久连接：只要任何一方没有明确提出断开连接，则保持tcp连接状态。
**http1.1中所有连接默认持久连接**
### 3、Cookie
http本是无状态协议，但服务端写入cookie并且由客户端保存cookie，下次请求会将cookie发送到服务端，服务端判断是从哪儿来的或一些身份信息等，以此来记录状态。
### 4、内容编码
在实体内容上进行的编码格式，保持信息原样压缩。  
gzip、compress、deflate、identity  
### 5、多部分对象集合(Multipart)
multipart/form-data  
multipart/byteranges  
### 6、获取部分内容的范围请求（range request）
Range: byte=1000~2000




