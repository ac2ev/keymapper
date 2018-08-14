Description
=====
* Keymapper - An Arduino-based hardware QWERTY keyboard layout remapper.
* Last updated: 26 November 2013 by darkytoothpaste
* Last updated: 13 August 2018 by gdsports

What you can do with it?
====
1. You can design your own keyboard layout with real hardware support
2. You can cheat your friend with it or do some other evil things :P
3. Just think about it!


How to use this?
====
## Hardware support
* Arduino Leonardo with [Circuits@Home USB Host Shield 2.0](http://www.circuitsathome.com/products-page/arduino-shields/usb-host-shield-2-0-for-arduino-assembled)
* Teensy 2.0 with [Circuits@Home USB Host Shield for Arduino Pro Mini](http://www.circuitsathome.com/products-page/arduino-shields/usb-host-shield-for-arduino-pro-mini)
* [Teensy 3.6](https://www.pjrc.com/store/teensy36.html) with [USB Host Cable For Teensy 3.6](https://www.pjrc.com/store/cable_usb_host_t36.html)
* TBD [Teensy LC](https://www.pjrc.com/store/teensylc.html)  with [Circuits@Home USB Host Shield for Arduino Pro Mini](http://www.circuitsathome.com/products-page/arduino-shields/usb-host-shield-for-arduino-pro-mini)

## Hardware assemble
### Teensy 3.6 with USB host cable
1. Solder the header pins to the USB 5 pin connector. Plug in the USB host cable.

2. Install [Teensyduino](https://www.pjrc.com/teensy/td_download.html) package.

3. Select Board type: Teensy 3.6 and USB Type: Keyboard. Upload the sketch.

4. Plug your USB keyboard to the USB Host shield

5. Done! Happy keyboard hacking :)

### Leonardo or Teensy 2
1. Stack the USB Host Shield on top of Arduino Leonardo, for Teensy, soldering work is required, you may refer to [this page](http://forum.colemak.com/viewtopic.php?id=1561)

2. Import [USB Host Shield 2.0 library](https://github.com/felis/USB_Host_Shield_2.0) to Arduino IDE

3. Connect the stack to your computer and upload the sketch

4. Plug your USB keyboard to the USB Host shield

5. Done! Happy keyboard hacking :)

### TBD Teensy LC

## Keyboard layout switching
* QWERTY is the default layout
* To change layout, press:
  - CTRL+SHIFT+0: QWERTY (Default)
  - CTRL+SHIFT+1: Tarmak1
  - CTRL+SHIFT+2: Tarmak2
  - CTRL+SHIFT+3: Tarmak3
  - CTRL+SHIFT+4: Tarmak4
  - CTRL+SHIFT+5: Colemak
  - CTRL+SHIFT+6: Dvorak
  - CTRL+SHIFT+7: Workman


Acknowledgement
===
Thanks to original author: [darkytoothpaste](https://github.com/darkytoothpaste/keymapper)

