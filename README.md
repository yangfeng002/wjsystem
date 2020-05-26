# wj应用系统

## 一、技术信息  
`1.技术支持`   
vue  
vue-cli  
vue-router  
axios/vue-axios    
element-ui  
nodeJs  
webpack  
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
       cd wjSys
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
>> build  //文件夹里是一些webpack的文件，配置参数什么的，一般不需要做修改（存放生产环境文件）  
>> config  //文件里是vue项目的基本配置文件 ，通常也不要修改
>> node_modules  //文件里是项目中安装的依赖模块（不提交） 
>> src   //源码文件夹，你写的代码基本上都放在这里面
    * -- assets  //资源文件，容易发生变化的文件  
    * -- components  //vue组件    
    * -- router  //路由文件    
    * -- App.vue  //公共组件     
    * -- main.js  //入口文件  
>> static    //静态资源放在这个目录下，这个目录下的资源文件默认是不会被打包压缩的  
>> test    //测试文件夹，测试都写在这里  
>> index.html   //默认首页文件  
>> .babelrc   //babel的配置参数，babel将ES6的语法进行编译  
>> .editorconfig  //看名字和内容应该是编辑器的配置文件  
>> .gitignore   //用来过滤一些版本控制的文件，比如node_modules/.idea等文件夹
>> .eslintignore //过滤eslint语法的  
>> index.html   //项目的主页  
>> package.json //是这个项目的一个文档说明，非常重要，在使用npm 安装依赖项的时候就是根据这个文件来的  
>> README.md  // 介绍自己这个项目的一个Markdown文件。  







