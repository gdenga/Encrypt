# 简单的加密示例
### DES+RSA加密

加密流程(服务器->客户端)：

1. 服务器客户端生成密钥对
2. 服务器客户端相互交换公钥
3. 生成随机DES密码
4. 使用DES加密数据
5. 使用客户端公钥RSA加密DES密码
6. 组合加密密码与加密数据

可以使用其他对称加密替换des