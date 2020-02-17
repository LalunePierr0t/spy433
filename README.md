# ST evalboard NUCLEO-F401RE Exploration


This example provides :

 *Features :*
 - [x] Board initialization
 - [x] LED Switch On/off
 - [x] User Button IT
 - [x] Virtual COM Port / CDC


*Description*

On each button the green LED toggles and message "LED Status changed!" is sent over CDC

*Project*

This project is done with STM32CubeIDE Version: 1.2.0 and STM32CubeMX Version : 5.5.0

Simply plug on the ST evalboard NUCLEO-F401RE on USB.

You can log the serial output use minicom (config 115200, I18n)


```
$ minicom -D /dev/ttyACM0
``` 

Press the blue button, you should get the following output:

```
Bienvenue avec minicom 2.7

OPTIONS: I18n 
Compilé le Nov 15 2018, 20:18:47.
Port /dev/ttyACM0, 10:29:29

Tapez CTRL-A Z pour voir l'aide concernant les touches spéciales

LED Status changed!
LED Status changed!
LED Status changed!
```

