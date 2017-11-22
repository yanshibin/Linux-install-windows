# Fork from https://moeclub.org/2017/11/19/483/
无DHCP时额外需求: iconv  
#Debian/Ubuntu  
一般自带  
#RedHat/CentOS  
yum install glibc-common  
# 使用示例:
`wget --no-check-certificate -qO DebianNET.sh 'https://moeclub.org/attachment/LinuxShell/DebianNET.sh' && bash DebianNET.sh -dd 'https://moeclub.org/get-win7embx86-auto'`


# 使用方法:
`wget --no-check-certificate -qO DebianNET.sh 'https://moeclub.org/attachment/LinuxShell/DebianNET.sh' && bash DebianNET.sh -dd '[Windows dd包直连地址]'`
# 萌咖提供的dd包:
```在你的机器上全新安装,如果你有VNC,可以看到全部过程. 
https://moeclub.org/get-win7embx86-auto
# 该包只添加了VirtIO驱动,理论上仅能在KVM,Hyper-V构架下正常运行.
# 如需在其他虚拟化构架下运行,请自行添加相关虚拟化驱动```  
  
  注意事项:
  远程登陆账号为: Administrator
  远程登陆密码为: Vicer
  仅修改了主机名,可放心使用.(建议自己制作.)
  如果因此违反了TOS,萌咖不负任何责任.
