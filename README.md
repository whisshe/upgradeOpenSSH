# upgradeOpenSSH
一键升级CentOS 6/7上的OpenSSH到新版本
## 使用方法
```shell
# 选择其中的序号进行升级
[root@localhost upgradeOpenSSH]# ./upgradeOpenSSH
 =================================================
     1. openssh7.8p1 with openssl1.0.2p
     2. openssh8.0p1 with openssl1.1.1g
     3. openssh8.2p1 with openssl1.1.1g
     q/quit to quit this menu
 =================================================
choose the order number to upgrade: 
```
## 脚本运行完后
```
source /etc/profile.d/openssh.sh
或者重新开一个新的ssh连接
然后即可检查ssh是否升级成功
ssh -V
```
