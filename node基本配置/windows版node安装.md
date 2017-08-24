# Nodejs安装——windows篇

## windows安装Node.js

[国外官网](https://nodejs.org/en/download/)和[国内官网](http://nodejs.cn/download/), 务必找准电脑型号, 否则会安装失败或无法运行.

安装的时候一直next就行

安装完后, 打开cmd命令行, 运行```node -v```, 如果出现版本号字段, 表示安装成功

## windows安装gitBash
GitBash是类似于Linux的命令行, 比起Windows的CMD命令行好用些, 如果您习惯cmd命令行, 则不必安装GitBash
[官方网站](https://git-scm.com/downloads), (不FQ的话)下载比较慢, 稍安勿躁, 安装的时候一直next就行

安装完后, 打开gitBash, 运行```node -v```, 如果出现版本号字段, 表示安装成功

## npm库与yarn库
强大性毋庸置疑, 由于npm库已经被集成在node包中, 所以直接运行```npm -v```, 如果出现版本号字段, 表示安装成功
yarn库还需要使用npm安装(全局): ```npm install -g yarn```, 安装完后, 运行```npm -v或npm -version```, 如果出现版本号字段, 表示安装成功

## npm 基本参数
```-g: 全局安装; 如: npm install -g react```
```--save: 安装到项目中并保存到package.json; 如: npm install --save react-router```



