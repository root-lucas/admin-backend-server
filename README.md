### 服务器端 API 接口

基于 `express + mongodb` 实现，需安装PC版`mongodb`数据库软件并启动。

运行方式：

```bash
# 需要nodemon插件
npm install nodemon -g 
npm install
npm run dev 

启动后可浏览器查看测试地址：http://localhost:3009
```

客户端页面项目代码：[点这里跳转](https://github.com/root-lucas/react-admin-backend)

这里可以详细阅读：[API使用文档](https://github.com/root-lucas/admin-backend-server/blob/master/api使用文档.md)

**API使用例子：**

默认登陆后端用户账号密码都是：admin   admin

管理后台登录：`http://localhost:3009/api/v1/auth/manager_login`

上传文件：`http://localhost:3009/api/v1/common/file_upload`