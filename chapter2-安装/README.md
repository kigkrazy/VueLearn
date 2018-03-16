## 独立安装
直接下载并用`<script>`标签引入，`Vue`会被注册为一个全局变量。
[开发者版本](https://vuejs.org/js/vue.js) : 包含完整的警告和调试模式
[生产版本](https://vuejs.org/js/vue.min.js) : 删除了警告，30.90KB min+gzip

具体代码参考demo中的`index-独立安装.html`。

## 使用CDN方法
CDN有三处：**BootCDN**、**unpkg**、**cdnjs**。

## npm方法
### 安装环境
1. 下载nodejs安装
2. 注册cnpm。[参考](http://npm.taobao.org/)  
命令行直接执行：
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```
3. 安装vue-cli  
```
# 全局安装 vue-cli
cnpm install --global vue-cli
```
### 生成用例

1. 生成用例
```
# 创建一个基于 webpack 模板的新项目
$ vue init webpack vue-demo
# 这里需要进行一些配置，默认回车即可
This will install Vue 2.x version of the template.

For Vue 1.x use: vue init webpack#1.0 vue-demo

? Project name vue-demo
? Project description A Vue.js project
? Author runoob <test@runoob.com>
? Vue build standalone
? Use ESLint to lint your code? Yes
? Pick an ESLint preset Standard
? Setup unit tests with Karma + Mocha? Yes
? Setup e2e tests with Nightwatch? Yes

   vue-cli · Generated "vue-demo".

   To get started:
   
     cd vue-demo
     npm install
     npm run dev
   
   Documentation can be found at https://vuejs-templates.github.io/webpack
```

2. 执行用例
```
$ cd vue-demo
$ cnpm install
$ cnpm run dev
 DONE  Compiled successfully in 4388ms

> Listening at http://localhost:8080
```

此时访问： [http://localhost:8080](http://localhost:8080)即可看到界面。


