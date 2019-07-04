# ubuntu_1804_preseed
personal fully automated preseed file for install ubuntu 18.04 server from PXE

issues


not working , still use archive.ubuntu.com after install.
but proxy part works , it did exist in /etc/apt/apt.conf

```
d-i mirror/country string tw
d-i mirror/http/proxy string http://192.168.0.2:3142
d-i mirror/http/hostname string ftp.tw.debian.org
d-i mirror/http/directory string /ubuntu
d-i mirror/http/mirror select ftp.tw.debian.org
```
