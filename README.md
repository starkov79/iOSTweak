# Writing iOS tweak on Windows using Theos

First of all you need an Ubuntu emulator. You can download it from Microsoft Store by this [link](https://www.microsoft.com/store/productId/9NBLGGH4MSV6).

You will also need [Theos](https://github.com/theos/theos) suite of tools. Installation guide you can found [here](https://github.com/theos/theos/wiki/Installation).

To start developing tweaks follow the next steps:
- Open Ubuntu simulator and log in as the superuser using command "sudo -i"
![Alt text](temp/1.jpg?raw=true "Title")
- Type next command "cd /home/username" where "username" is your PC user name
- To launch Theos application type "theos". If you see a message "command not found" then use an absolute link to app "/opt/theos/bin/nic.pl"
