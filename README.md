## Tiny Reflow Controller V4

The key part of the code in this repository is based on Rocket Scream's TinyReflowController and [a solder reflow hot plate](https://www.e-tinkers.com/2021/07/converting-uyue-preheater-into-a-solder-reflow-hot-plate/). 

I didn't use the Rocket Scream's TinyReflow Controller hardware neither, instead I built based on [ElectroNoobs](https://electronoobs.com/eng_arduino_tut161.php) design. An Arduino nano, an LCD 16x2, an SSR, and a Thermisthor. 


> ## Disclaimer
> Dealing with high voltage is a very dangerous act! Please make sure you know what you are dealing with and have proper knowledge before hand. Your use of any information or materials on this Tiny Reflow Controller is entirely at your own risk, for which we shall not be liable.

## Dependencies
The firmware has the dependencies of several Arduino Libraries, if you are using PlatformIO, it has been setup under the `lib_deps` directive in the `platformio.ini`.

  - [Arduino PID Library](https://github.com/br3ttb/Arduino-PID-Library)
  - [SSD1306Ascii Library](https://github.com/greiman/SSD1306Ascii)
  - [Button Arduino Library](https://github.com/e-tinkers/button)
  - [MAX31855 Arduino Library](https://github.com/e-tinkers/MAX31855)


## Schematic
The interconnection of various parts is outlined in [schematic](https://github.com/e-tinkers/TinyReflowControllerV3/blob/master/resources/TinyReflowControllerV3.pdf). The Solid State Relay and Thermocouple are re-used with the parts that came with the UYue Preheater.

## Licences

This Tiny Reflow Controller hardware and firmware are released under the [Creative Commons Share Alike v3.0 license](http://creativecommons.org/licenses/by-sa/3.0/). You are free to take this piece of code, use it and modify it. All we ask is attribution including the supporting libraries used in this firmware.


