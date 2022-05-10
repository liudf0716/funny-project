## 介绍

nnn是一款支持在linux终端环境下使用的文件管理系统，其支持鼠标及键盘快捷键操作；



项目地址：

https://github.com/jarun/nnn

## 安装环境

Ubuntu 20.04.3 LTS \n \l


## 下载最新的代码
```
wget https://github.com/jarun/nnn/archive/refs/tags/v4.5.tar.gz
```

## 编译安装

```
sudo apt-get install pkg-config libncursesw5-dev libreadline-dev
sudo make strip install
```

## 演示



## 使用与退出

编译完成后执行``nnn`命令即可进入文件管理界面，进入nnn界面后，可以通过鼠标来操作

- 删除文件

选择文件后按x键，回车输入y

- 进入当前目录

选择目录后，^+] 键退回终端操作界面，当前工作目录为在nnn界面中选择的目录

- 退出界面

连续按2次esc键

更多玩法参考官方文档：

https://github.com/jarun/nnn/wiki/Usage



