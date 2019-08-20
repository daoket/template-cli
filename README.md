##### 前言 写项目的时候，每次写组件的时候都需要重新新建 js,js 里面需要写重复的代码，所以就想偷个懒，然后写了一个根据命令生成组件的 npm 包

##### 安装方法

```
sudo npm i template-cli-wtniu -g
```

#### 使用方法

```
temp init 模块名称
```

比如: temp init Header

#### 流程

- temp init Header
- 终端中会提示请选择模版类型?
- 模版类型有 1 种,选择相应的组件类型(下面有类型说明)
- 然后就等待下载模版
- 终端提醒模版创建成功,流程结束

#### 组件类型说明

- react-component------ES6 组件:包含生命周期的 React.Component 组件

#### 组件模版地址:https://github.com/daoket/template 
#### 完成脚手架地址:https://github.com/daoket/template-cli

#### npm发布流程

- 在https://www.npmjs.com/中注册账号(如果有请忽略)
- npm adduser 相应输入用户名，密码，邮箱
- npm version patch 修改版本号（修改过后需要改版本号，如果不修改版本号会报错）
- npm publish 就可以看到提交了（只支持npm提交，如果用了淘宝镜像注意切换）


测试：

node index.js init A

目前仅支持一种模板，暂不支持添加多个模板


