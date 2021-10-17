系统支持 Debian 9+/Ubuntu 20.04+/Centos 7+
------------------
## 半自动安装 ##
wget -N --no-check-certificate https://raw.githubusercontent.com/magicLBin/ss5/main/ss5.sh && bash ss5.sh

## 命令报错的话 请安装wget ##
yum -y install wget 或者 apt -y install wget

## 全自动安装（用户和端口全默认） ##
 <pre><code>wget -q -N --no-check-certificate https://raw.githubusercontent.com/magicLBin/ss5/main/install.sh && bash install.sh</code></pre>

## 相关文件路径 ##
- 1.端口文件<br>
 /etc/sysconfig/ss5<br>
- 2.访问授权配置文件<br>
 /etc/opt/ss5/ss5.conf<br>
- 3.用户账号信息文件<br>
 /etc/opt/ss5/ss5.passwd<br>
- 4.部分文件修改后需要重启ss5<br>
 重启命令:service ss5 restart<br>
