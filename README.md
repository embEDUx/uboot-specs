### Write firmware img to sd card

[Utilite Wiki](http://www.compulab.co.il/utilite-computer/wiki/index.php/Utilite_U-Boot_Update)

```bash
dd if=cm-fx6-firmware of=/dev/mmcblk0 bs=1K skip=1 seek=1 oflag=dsync
```
