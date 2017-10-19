# Samba
Samba Server Configure

1.安装samba
sudo apt-get install samba samba-common 

2.添加samba访问用户
sudo smbpasswd -a username

3.可能需要的包
sudo apt-get install python-glade2 gksu

4.安装图形化配置工具
sudo apt-get install system-config-samba

5.启动图形化配置工具
sudo system-config-samba

6.如果报错
sudo touch /etc/libuser.conf

7.重启服务
sudo service smbd restart
