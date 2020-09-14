# vue-cli-npm

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

+ 注册npm账户

+ `npm adduser`

+ `npm publish`

  到这一步基本发布成功，载NPM官网个人资料中可以看到发布的包

+ 上传后可以设置成原先的地址

  ```
  npm config set registry=https://registry.npm.taobao.org/
  ```

  



### 发布成功后使用方法

+ 全局安装npm包

  ```
  npm i vue-rem-cli -g
  ```

+ 创建项目

  ```
  vue-cli init vue-pc-demo
  ```

  





