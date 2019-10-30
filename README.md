### XDEBUG的配置

>> 通过XDEBUG的配置可以很容易的设置断点调试。

//Linux挂载window上共享文件夹挂
mount -t cifs -o username='nbasus',password='',dir_mode=0777,file_mode=0777,vers=3.0 //192.168.17.190/share  /share
//永久挂载r
vim /etc/fstab 
mount -t cifs -o //192.168.17.43/share  /share cifs username=administrator,password=123 0 0

//192.168.17.43/share  /share  cifs  defaults,auto,username=administrator,password=123

//192.168.17.43/share  /share cifs username='nbasus',password='751011029',dir_mode=0777,file_mode=0777,vers=3.0 0 0


	
	
