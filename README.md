# IP Hunter for Huawei Modem

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Hunt public IP 113.211

requirement : Huawei Modem with AIO installed

Follow these steps:

1. Download console app like Shelly for iOS, Putty SSH for Android or Putty for PC.

2. Open the app and login to root@192.168.8.1 port 22

3. Copy this command and paste it in the console app :

```
rm -rf iphunter && busybox wget -q https://raw.githubusercontent.com/abidarwish/IP-Hunter-for-Huawei-Modem/main/iphunter && bash iphunter
```

4. Follow instructions on the screen and wait until your modem connects to the intended public IP

<I>The next time you want to run the script, just type `bash iphunter` in the console app</I>
