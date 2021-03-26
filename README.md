# my-build-cli

## npm发布

### 检测registry

+ 获取registry信息

  ```
  npm config get registry
  ```

+ 设置使用的registry信息

  ```
  npm config set registry=http://registry.npmjs.org
  ```

+ 注册/登录npm账户

+ `npm adduser`

+ `npm publish`

  到这一步基本发布成功，在npm官网个人资料中可以看到发布成功的包

+ 上传后可以恢复设置成原先的地址

  ```
  npm config set registry=https://registry.npm.taobao.org/
  ```

  

### 发布成功后使用方法

+ 全局安装npm包

  ```
  npm i my-build-cli -g
  ```

+ 创建项目

  ```
  my-build-cli init projectName
  ```

  





