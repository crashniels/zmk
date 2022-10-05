# Corsair K95 RGB Platinum (XT)

Compile using 

``west build -p -b lpcxpresso11u68 -- -DSHIELD=k95_rgb_platinum``

and copy using

``dd if=build/zephyr/zmk.bin of=path/to/your/crp_disabled/firmware.bin bs=512 conv=notrunc oflag=direct,sync``
