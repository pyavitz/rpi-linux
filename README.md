# [Raspberry Pi Linux Kernels](https://github.com/pyavitz/rpi-img-builder)
### Supported: [Debian, Devuan & Ubuntu](https://github.com/pyavitz/binary/releases/tag/images)
**Download installer**

```sh
if [ `command -v fetch` ]; then
      fetch -u;
else
      sudo wget -cq https://github.com/pyavitz/scripts/raw/master/fetch -P /usr/local/bin;
      sudo chmod +x $(command -v fetch);
      fetch -h;
fi
```
```sh
Fetch, Linux kernel installer for the Raspberry Pi Image Builder
https://github.com/pyavitz/rpi-img-builder
Usage: fetch -h

   -1       Linux 5.15.y LTS
   -2       Linux Stable Branch
   -f       Update Wifi/BT Firmware
   -U       Update Raspberry Pi Userland

   -u       Update Fetch

Should you come across any bugs, either open an issue on GitHub or talk
with us directly by joining our channel on Libera; #arm-img-builder
```
