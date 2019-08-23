# wj应用系统

## 一、技术信息  
`1.技术支持`   
vue  
vue-cli  
element-ui  
nodeJs  
mysql  

`2.开发工具`  
webstorm  
HbuildX  
idea 

---

## 二、环境搭建

### 1.安装
```bash
1.1 安装node
    安装nodejs
    node-v/npm -v
    安装cnpm
    npm install -g cnpm --registry=https://registry.npm.taobao.org
    
1.2 安装webpack
    npm install webpack -g
    查看版本号：webpack -v
    webpack脚手架
    npm install webpack-cli -g
    
1.3 安装vue
  npm install vue
  查看版本号：vue -V

1.4 安装vue-cli
  npm install --global vue-cli    
    
1.5 安装路由
npm install vue-router

    
```
*** 
### 2.实例
```bash
   2.1 创建一个基于webpack模板的项目
   vue init webpack wjSys
   
   2.2 切换路径，安装依赖（install dependencies）
       cd my-project
       npm install
   
   2.3 部署运行（serve with hot reload at localhost:8080）
       npm run dev
   
   2.4 生产构建 build for production with minification
       npm run build
   
   2.5 build for production and view the bundle analyzer report
      npm run build --report
   
   
```

_ _ _

## 三、项目结构解析

> wjSys  
>> build  //webpack相关配置文件（存放生产环境文件）  
>> config  //webpack相关配置文件  
>> node_modules  //（模块化,不提交）  
>> src   //开发环境文件
    * -- assets  //资源文件，容易发生变化的文件  
    * -- components  //vue组件  
    * -- router  //路由文件  
    * -- App.vue  //公共组件  
    * -- main.js  //入口文件  
>> static  //静态资源文件，不会打包到build中，很少改变的文件  
>> test  //测试  
>> index.html //默认首页文件



