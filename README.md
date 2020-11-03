# Esp32 Atari Breakout Game

Migration of `Volos Projects` [Danko Bertović](https://www.youtube.com/c/VolosProjects/featured) game from Arduino IDE to PlatformIO but it is compatible with Arduino too.

## Mod features added

- [x] Auto suspend for save battery
- [x] Restart the game with right button also with reset botton
- [x] ESP light sleep for delay implementation for save battery
- [x] Saved top record in ESP32 flash via Preferences library
- [x] Show battery level (only in the first game over screen)
- [ ] Battery level issue (refresh fails sometimes)

## Compiling

For compiling and installing, please install first [PlatformIO](http://platformio.org/), the open source ecosystem for IoT development compatible with **Arduino**, and its command line tools (Windows, MacOs and Linux), and run the next line in the project directory with your TTGO-Tdisplay connected to USB port:

``` bash
pio run --target upload
```

## 3D print case VIDEO

[![TTGO T-Display game console case](https://img.youtube.com/vi/P4lxfTi-EXg/0.jpg)](https://www.youtube.com/watch?v=P4lxfTi-EXg)

TTGO T-Display game console case on [Youtube](https://www.youtube.com/watch?v=P4lxfTi-EXg)

---

## Credits

Original source code was posted on [Volos projects](https://www.youtube.com/c/VolosProjects/featured) channel.

[![TTGO Display Breakout Atari game](https://img.youtube.com/vi/N6V7ZJkhSbc/0.jpg)](https://www.youtube.com/watch?v=N6V7ZJkhSbc)

