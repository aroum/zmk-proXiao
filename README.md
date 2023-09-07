# zmk-proXiao

## Enki42
  
ZMK config fo proXiao shields. 


proXiao is a bluetooth controller for:

* [Corne](https://github.com/aroum/proXiao/tree/corne)
* [Jorne](https://github.com/aroum/proXiao/tree/jorne)
* [Enki42](https://github.com/aroum/proXiao/tree/enki42)
* [Fifi](https://github.com/aroum/proXiao/tree/fifi)
* [Lily58](https://github.com/aroum/proXiao/tree/lily58)
* [Sofle](https://github.com/aroum/proXiao/tree/sofle)
* [reviung41](https://github.com/aroum/proXiao/tree/reviung41)

Support for Lily58, Sofle, reviung41 is implemented only on PCB v3. Screens and backlight are not supported. FTo support encoders, you need PCB v3 and solder an additional wire.

---

By switching between branches in this repository, you can choose the configuration for your keyboard. For a Corne or other compatible 6-column keyboard, you should select the ```corne``` branch.

If you have problems, flash the firmware to clear the settings from the branch [setting-reset](https://github.com/aroum/proXiao/tree/setting-reset).

You can change the device name in file ```config/proXiao.conf```  in line
```
CONFIG_ZMK_KEYBOARD_NAME="proXiao"
```

---

Pre-build firmware can be downloaded in the [releases](https://github.com/aroum/proXiao/releases).

