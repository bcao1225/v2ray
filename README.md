# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本

# 搭建教程
以下教程需要复制下方脚本到xshell执行，请大家结合文字和脚本仔细查看

## 第一步：

我们先检查一下系统是否安装了git

git --version
如果提示“git version 1.8.3.1”这类提示，直接就可以看第二步教程了

如果提示“-bash: git: command not found”，我们需要先使用下面命令安装git

yum -y install git
等待安装完成在执行一次“git --version”测试。

如果出现其他问题，请参考：linux git命令报错解决办法

## 第二步：

从github拷贝代码

git clone https://github.com/lizhongnian/v2ray
进入v2ray目录

cd v2ray
给安装脚本赋予执行权限

chmod +x install.sh

## 第三步：

执行安装脚本

./install.sh
