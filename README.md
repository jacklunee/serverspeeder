# serverspeeder锐速一键破解安装版

# 特别说明
另外：重要的事情说三遍！！！

锐速不支持Openvz！！！锐速不支持Openvz！！！锐速不支持Openvz！！！

### 你可能需要：
* 如果你不知道你的机子到底是不是Openvz，请食用[《教程：一键检测VPS是Openvz还是KVM还是Xen》](http://www.91yun.co/archives/836)
* 如果你的内核不对，是Centos的话请食用[《教程：CentOS更换内核，提供锐速可用的内核下载》](http://www.91yun.co/archives/795)。debian和ubuntu我不熟，暂时还没一键包，请自行百度google。。



# 锐速破解版安装方法：
    wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh
# 锐速破解版卸载方法：
    chattr -i /serverspeeder/etc/apx* && /serverspeeder/bin/serverSpeeder.sh uninstall -f

—————————————————————————————————————
# 锐速破解版安装方法（旧版本代码）：

第一步安装SS或V2ray

—————————————————————————————————————
第二步 更换内核 然后重启
CentOS7

rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-3.10.0-229.1.2.el7.x86_64.rpm --force

——————————————————————————————————————
第三步   安装旧的代码  然后选择 1

wget -N --no-check-certificate https://raw.githubusercontent.com/jacklunee/serverspeeder/master/serverspeeder-all.sh && bash serverspeeder-all.sh

成功


锐速破解版功能：
如果内核完全匹配就会自动下载安装。
如果没有完全匹配的内核，会在界面提示可选内核，可以手动选个最接近的尝试
自动下载授权文件
自动修改配置文件
已chattr +i /serverspeeder/etc/apx*禁止修改配置文件，可以不用加hosts了
目前只支持CentOS，ubuntu和debian。如果有其他系统支持，可以到[91yun.org我的博客](http://www.91yun.co/serverspeeder91yun)手动下载其他系统的安装包
