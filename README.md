# download and install

open <https://www.vmware.com/products/workstation/>

download and install workstation
![download_workstation](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/download_workstation.png "download_workstation")

>1F04Z-6D111-7Z029-AV0Q4-3AEH8 for 11.0.0

>5A02H-AU243-TZJ49-GTC7K-3C61N for 12.1.0

>ZC5XK-A6E0M-080XQ-04ZZG-YF08D for 14.0.0

***
# change language

open vmware workstation install folder and enter the messages sub-folder

![language_folder](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/language_folder.png "language_folder")

remove or rename the language folder (ie. zh_CN) and reboot the vmware workstation

***
# create virtual mechine

![new_virtual](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/new_virtual.png "new_virtual")
![install_later](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/install_later.png "install_later")
![select_os](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/select_os.png "select_os")
go on the next to finish

***
# setup virtual mechine

![edit_settings](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/edit_settings.png "edit_settings")
![browse_iso](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/browse_iso.png "browse_iso")
![power_on](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/power_on.png "power_on")
e.g. see ubuntu installation at <https://ouiyeah.github.io/ubuntu/>
![unmount_iso](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/unmount_iso.png "unmount_iso")
![network_settings](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/network_settings.png "network_settings")

***
# install vmware tools

install open vmware tools (recommended)

>$ sudo apt-get install open-vm-tools open-vm-tools-desktop

install deprecated tools as follow (unrecommended)

![load_tools](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/load_tools.png "load_tools")
![copy_tools](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/copy_tools.png "copy_tools")
![extract_tools](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/extract_tools.png "extract_tools")
![install_tools](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/install_tools.png "install_tools")

>$ cd vmware-tools-distrib

>$ sudo ./vmware-install.pl

press enter again and again to finish

set display to auto fit guest

![display_settings](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/display_settings.png "display_settings")

reset virtual network after installing another virtual machine e.g. virtualbox

![virtual_network](https://raw.githubusercontent.com/ouiyeah/vmware/master/img/virtual_network.png "virtual_network")
