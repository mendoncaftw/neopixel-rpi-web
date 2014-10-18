neopixel-strip-server
=====================

Simple **Flask** application for the **Raspberry Pi** that shows a **color picker** and changes the led color on your **NeoPixel strip**.

It's using the color picker from https://github.com/josedvq/colpick-jQuery-Color-Picker and the NeoPixel Python lib from https://github.com/jgarff/rpi_ws281x.

Just follow the installation instructons on both.

If you are familiar with [Flask](http://flask.pocoo.org/) and  assuming you have configured the number of LEDs you are using and the GPIO PIN number in the *leds.py* file, just stand on the project's root folder and type on the terminal:

```
sudo python leds.py
```

Go to the browser and type your RPi's address and you should see the color picker. Now you just need to keep selecting colors.
