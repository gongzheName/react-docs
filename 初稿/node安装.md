# Nodejs安装——Linux篇

## Linux安装Node.js

Node.js提供源码安装和安装包安装两种方式，对Linux操作不熟悉，但又想在Linux上使用Node开发，可以使用Linux安装包管理工具安装。

### Node.js源码安装

这是在Ubuntu上的源码安装

从Github上获取Node.js源码

```sh
$ sudo git clone https://github.com/nodejs/node.git
```

修改目录权限

```sh
$ sudo chmod -R 755 node
```

执行下面命令安装。

```sh
$ cd node
$ sudo ./configure
$ sudo make
$ sudo make install
```

查看Node.js是否安装成功

```sh
$ node --version
```

### 包管理器安装

Node官网提供编译好的Linux安装包，如果你的Linux能使用官网提供的包安装，那就方便许多，如果是Archlinux之类的系统，可以通过系统的包管理器安装

**Archlinux上的安装方法**

```sh
$ sudo pacman -S nodejs
$ sudo pacman -S npm
# 如果安装了yaourt可以使用下面的方法安装
$ yaourt -S nodejs
$ yaourt -S npm
```

### Ubuntu 命令安装

```sh
sudo apt-get install nodejs
sudo apt-get install npm
```