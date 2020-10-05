# Win10_install_Ubuntu
Win10, how to install Ubuntu support natively

### Windows Subsystem for Linux Installation Guide for Windows 10
####it is not allowed by deflaut, https://docs.microsoft.com/en-us/windows/wsl/install-win10

#### or use GUI to do the job as following,

Enable this feature support first,  
Win10, 本機, 控制台\程式集\程式和功能  
![enable_win10_linux_support_1.jpg](/photos/enable_win10_linux_support_1.jpg)
  
  
![enable_win10_linux_support_2.jpg](/photosenable_win10_linux_support_2.jpg)

select this feature to proceed with
![enable_win10_linux_support_3.jpg](/photosenable_win10_linux_support_3.jpg)

upon finish, Win10 will be asked to reboot.


### Win10 support Linux is enable, now to install Ubuntu 20.04.1 LTS  
open Microsoft Store, the app store by Microsoft, just like play sotre of Google or App store of Apple.  
fine Untutu and install, may be hours requried  
![enable_win10_linux_support_4.jpg](/photosenable_win10_linux_support_4.jpg)  

### Ubuntu 20.04.1 LTS in installed, the first time invoke
the systme will asks you to select user name and password at the first itme,
for example,
```
user name : xiao  
password : 0000  
```
easy for development paltform and internally used;  


### Ubuntu 20.04.1 LTS, login and update the system  
```  
sudo apt-get update    
```  
![enable_win10_linux_support_6.jpg](/photosenable_win10_linux_support_6.jpg)  
required hour depends on speed of your network  


### Ubuntu 20.04.1 LTS, ready for the job
caution, do not edit any of those file with Win10 tools or folder manipulation!!
where to see those files of linux working enviorment, usually,
```   
%userprofile%\AppData\Local\Packages\CanonicalGroupLimited.Ubuntu20.04onWindows_79rhkp1fndgsc
```   
and roots
```  
%userprofile%\AppData\Local\Packages\CanonicalGroupLimited.Ubuntu20.04onWindows_79rhkp1fndgsc\LocalState\rootfs
```  
and home folder
```  
%userprofile%\AppData\Local\Packages\CanonicalGroupLimited.Ubuntu20.04onWindows_79rhkp1fndgsc\LocalState\rootfs\home
```  


something like this,  
![enable_win10_linux_support_7.jpg](/photosenable_win10_linux_support_7.jpg)  
