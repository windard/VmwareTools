#VmwareTools 
I find it's too difficult to insatll---------VmwareTools
So,I hope this will be useful in the future~

It is useful in Vmware 9.0.
MwareTools-9.6.0-1294478.tar.gz is used for Linux.(such as Ubuntu.CentOS.Kali,I hava spent lots of time on them to fix the screen)
Windows.iso is used for WIndows.(such as windows XP.windows 10.windows server 2003)
Linux.iso (I don't think it's useful,but who knows ?)


MY WAY:
1.FOR LINUX :
- 拷贝至Linux系统中(可以用U盘，也可以直接下载到Linux系统中)
- $ tar xzf VMwareTools-9.6.0-1294478.tar.gz
- $ cd vmware-tools-distrib
- $ sudo ./vmware-install.pl
- 一路打Enter

2.FOR WINDOWS :
- 打开虚拟机 '设置' 选择 'CD/DVD'
- 选择'使用ISO镜像文件' 选取Windows.iso
- 在虚拟机内的挂载的光盘上直接运行
