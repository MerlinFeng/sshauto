# sshauto
password.lst 为虚拟机列表

1:192.168.56.12:20001:root:root:开发机

2:192.168.56.65:10001:fengqiang:fengqiang.pem:开发机:g5XiEnSorBkUoXOT

### 注意
使用前确定已经安装expect 自行google 
yum install expect # centos
brew install expect # mac
apt-get install ecpect # ubuntu

### 说明

序号：ip：端口号：账号：密码/pem文件：备注：（pem密码）

密钥 pem文件放在keys文件夹下

### 添加别名

alias sshauto='/Users/fengqiang/sshauto/so.sh' #对应自己的目录位置
thx 
