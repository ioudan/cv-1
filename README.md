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
## 打包，并指定公共资源的路径
每次改完代码，必须运行一次，才能正确请求JS和CSS
```
//本次上传git的学习中，正确
λ parcel build src/index.html --public-url .   
main.e8b986df.js
style.4430865c.css


λ parcel build src/index.html --public-url dist   
dist/main.e8b986df.js
dist/style.4430865c.css

λ parcel build src/index.html --public-url /
/main.e8b986df.js
/style.4430865c.css

```