# ngrok
ngrok一键安装脚本，适用于Centos版本服务器  
默认安装路径  
git：/usr/local/git  
go：/usr/local/go  
ngrok：/usr/local/ngrok 
##################################################################################################################
A:install-ngrok.sh

wget --no-check-certificate https://github.com/soulCoke/ngrok-onekey/install-ngrok.sh -O ./install-ngrok.sh

chmod 500 ./install-ngrok.sh

./install-ngrok.sh install
#####################################################################################################################
B:onekey-ngrok.sh

wget --no-check-certificate https://github.com/soulCoke/onekey-ngrok.sh -O ./onekey-ngrok.sh

chmod 500 ./onekey-ngrok.sh

./onekey-ngrok.sh install
###################################################################################################################
C:ngrok.sh

wget --no-check-certificate https://github.com/soulCoke/ngrok-onekey/ngrok.sh -O ./ngrok.sh

chmod 500 ./ngrok.sh

./ngrok.sh install
#######################################################################################################################
D:sunnyos-ngrok.sh

wget --no-check-certificate https://raw.githubusercontent.com/xj888xj/ngrok-onekey/master/sunnyos-ngrok.sh -O ./sunnyos-ngrok.sh

chmod 500 ./sunnyos-ngrok.sh

./sunnyos-ngrok.sh install

########################################################################################################################
脚本地址：
https://github.com/sunnyos/ngrok

用法：git clone https://github.com/sunnyos/ngrok
然后参照上面说明。

#客户端编译好存放的路径：
	/usr/local/ngrok/bin/  
需要根据客户端的操作系统环境编译，脚本也已经写好

详细教程看博客：[www.sunnyos.com](http://www.sunnyos.com "Sunny博客")  
搭建好免费提供的ngrok服务：[www.ngrok.cc](http://www.ngrok.cc "www.ngrok.cc")  
