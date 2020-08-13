# tab-root

# Glossary

* PIT-file: file with partitions
* ADB Sideload: the command that allows you to transfer the Android system installation file (it is always a .zip file) and install it directly on the phone, from the PC.

# Flashing

1) Install flasher:

```
sudo apt install heimdall-flash
```

2) Dowload [TWRP ](https://twrp.me/samsung/samsunggalaxynote101.html)

3) Boot to download (fastboot) mode using buttons "power" + "volume down"

4) Type in desctop:

```
heimdall flash --RECOVERY twrp-2.8.7.0-gt-n8000.img --no-reboot
```

5) After transfer completes and blue line shown boot to recovery mode using "power" + "volume up" keys. 
This required because boot to OS will overwrite custom recovery with default.

6) Install sudo from TWRP
* [MAGISK](https://github.com/topjohnwu/Magisk)
* SuperSU from TWRP


