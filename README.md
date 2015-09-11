matrix
======
5 8x8 LED matrixes in series, controlled by an arduinoProMicro displays variable text depending on day/time determined by an RTCmodule on a seperate proMicro

The 8x8 LED matrixes are from [Linksprite](http://linksprite.com/wiki/index.php5?title=LED_Matrix_Kit)

Components
==========

  * Control: An arduino pro micro from ebay
  * Output: 5 [Linksprite LED matrixes](http://linksprite.com/wiki/index.php5?title=LED_Matrix_Kit)

what?!
======

The 8x8 led modules share VCC, GND, DATA, and CLK pins and have seperate CS (Chip select) pins.
The RTC module is thoroughly examined [here](https://learn.adafruit.com/ds1307-real-time-clock-breakout-board-kit)