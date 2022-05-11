# SecretChatRoom
### 诡秘聊天室
- 快速搭建web聊天室
- 基于IMSDK的webdemo改编
- clone自https://github.com/TencentCloud/TIMSDK/tree/master/Web
- 已改为可映射到外部域名

##### 运行前
- 需要配置 `/public/debug/GenerateTestUserSig.js` 文件中的 `SDKAppID` 和 `SECRETKEY`
- id和密钥去腾讯云的服务页面申请（产品号269）https://cloud.tencent.com/document/product/269  

##### 本地运行
- 需要node环境
```
npm install
npm start
```

##### Docker容器
```
docker build --pull --rm -f "DockerFile" -t secretchatroom:[版本号] "." 

```

By:tyza66(洮羱芝闇)
