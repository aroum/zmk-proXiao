# zmk-proXiao
  
ZMK config fo proXiao shields. 


proXiao is a bluetooth controller for:

* Corne
* Jorne
* Enki42
* Fifi
* Lily58 
* Sofle
* reviung41

Support for Lily58, Sofle, reviung41 is implemented only on PCB v3.

---

By switching between branches in this repository, you can choose the configuration for your keyboard. For a Corne or other compatible 6-column keyboard, you should select the ```corne``` branch.

If you have problems, flash the firmware to clear the settings from the branch ```setting-reset```.

You can change the device name in file ```config/proXiao.conf```  in line
```
CONFIG_ZMK_KEYBOARD_NAME="proXiao"
```
