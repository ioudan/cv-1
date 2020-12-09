# 准备工作

## 安装parcel
```shell
λ yarn global add parcel

λ yarn global add parcel@1.12.3
```
## 启动服务器
```
λ yarn global add parcel

Server running at http://localhost:1234
```
## 打包，并指定公共路径
```
λ parcel build src/index.html --public-url dist
λ parcel build src/index.html --public-url /
λ parcel build src/index.html --public-url .   //本次上传git的学习中，正确
```