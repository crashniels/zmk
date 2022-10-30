# Corsair K70 RGB

Compile using 

``west build -p -b k70_rgb``

and copy using

``dd if=build/zephyr/zmk.bin of=path/to/your/crp_disabled/firmware.bin bs=512 conv=notrunc oflag=direct,sync``
