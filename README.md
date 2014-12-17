### Write firmware img to sd card

```bash
dd if=cm-fx6-firmware of=/dev/mmcblk0 bs=1K skip=1 seek=1 oflag=dsync
```
