# sock5
sock5

选择的服务器系统：centos7

SSH到服务器，依次执行下面的代码：（每一行需要分别执行）

sudo su root
yum -y install wget
get –no-check-certificate https://raw.github.com/Lozy/danted/master/install.sh -O install.sh
bash install.sh --port=8888 --user=admin --passwd=123456

代码执行完成，这样你就搭建了属于自己的Socks5代理，ip是就是服务器ip地址，端口：8888 用户名：admin 密码：123456

