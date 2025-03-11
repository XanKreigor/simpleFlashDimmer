Flash Light dimming utilty for Xiaomi 14T Pro Note:device already supports but root required for precise control

**Requires Root for precise control**

Features:
- Dark Mode
- Mostly Works
- Dimms your flashlight

Mostly ChatGPT'd together in a few minutes but it does what it's supposed to do

Note that it has not been tested but might work on other devices. It just does `echo BRIGHTNESS_VALUE > /sys/class/flashlight_core/flashlight/flashlightbrightness`, cou can change the file path to whatever you want in the MainActivity to potentially support other devices.

Add your own devices:

In the Cis utilty you can dim the flashlight, then just connect you PC and run `adb logcat | grep flash` to find the filepath
