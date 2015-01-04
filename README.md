### Write firmware img to sd card

[Banana Pi Wiki](http://linux-sunxi.org/Bootable_SD_card#Bootloader)

```bash
dd if=u-boot-sunxi-with-spl.bin of=${card} bs=1024 seek=8
```

