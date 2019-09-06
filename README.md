Lolin esp32 nggo nara
=====================

Ini adalah board lolin esp32 yang sudah terinstall micropython punya nara

Pinout
------

![lolin-esp32-lite-pinout](https://github.com/chenull/lolinara/raw/master/lolin-esp32-lite-pinout.jpg "Lolin esp32 lite pinout")

Links
-----

- Product Page: [LOLIN32 Lite](https://wiki.wemos.cc/products:lolin32:lolin32_lite)
- [Micropython](http://micropython.org)
- [Dokumentasi ESP32 di Micropython](http://docs.micropython.org/en/latest/esp32/quickref.html)
- [rshell](https://github.com/dhylands/rshell)

Cara upload `boot.py`
---------------------

```bash
rshell -b 115200 -p /dev/cu.usbserial-14330 cp boot.py /pyboard/boot.py
```

Schematic
---------

suk nek selo