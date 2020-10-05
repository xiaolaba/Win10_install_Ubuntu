# Win10_install_Ubuntu
Win10, how to install Ubuntu support natively

### Windows Subsystem for Linux Installation Guide for Windows 10
#### it is not enabled by default, see how to by M$   
https://docs.microsoft.com/en-us/windows/wsl/install-win10  

###  or use GUI to do the job as following,

Enable this feature support first,  
1. Win10, [本機], input [控制台\程式集\程式和功能\, then hits [ENTER]     
![enable_win10_linux_support_1.jpg](/photos/enable_win10_linux_support_1.jpg)  
  
2. open the setup, this window should pops up, clicks [開啟或關閉WINDOWS功呢]      
![enable_win10_linux_support_2.jpg](/photos/enable_win10_linux_support_2.jpg)  

3. select this feature to proceed with, [windows 子系統 LINUX 版], then press [確定]   
![enable_win10_linux_support_3.jpg](/photos/enable_win10_linux_support_3.jpg)  

just be patient and waiting.... upon finish, Win10 will be asked to reboot.    
  
  
### Win10 support Linux is enable, now to install Ubuntu 20.04.1 LTS  
now PC has been rebooted, open Microsoft Store, the app store by Microsoft. just like play store of Google or App store of Apple.  
find Ubuntu and install, maybe hour is required,  
![enable_win10_linux_support_4.jpg](/photos/enable_win10_linux_support_4.jpg)  

### Ubuntu 20.04.1 LTS in installed, the first time invoke  
the system will asks you to select user name and password at the first time,  
for example,  
```
user name : xiao  
password : 0000  
```
easy for development platform and internally used;  


### Ubuntu 20.04.1 LTS, login & update the system  
```  
sudo apt-get update    
```  
![enable_win10_linux_support_6.jpg](/photos/enable_win10_linux_support_6.jpg)  
required hour depends on speed of your network  


### Ubuntu 20.04.1 LTS, ready for the job  
caution, do not edit any of those file with Win 10 tools or folder manipulation!!  
where to see those files of linux working environment, usually,  
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


job done, something like this,  
![enable_win10_linux_support_7.jpg](/photos/senable_win10_linux_support_7.jpg)  
