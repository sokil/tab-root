# tab-root

# Glossary:

## PIT-file

File with partitions

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


