https://learn.adafruit.com/adafruit-agc-electret-microphone-amplifier-max9814/overview

The chip at the heart of this amp is the MAX9814,
and has a few options you can configure with the breakout.
The default 'max gain' is 60dB, but can be set to 40dB 
or 50dB by jumpering the Gain pin to VCC or ground. 
You can also change the Attack/Release ratio, 
from the default 1:4000 to 1:2000 or 1:500. 
The ouput from the amp is about 2Vpp max on a 1.25V DC bias,
so it can be easily used with any Analog/Digital
converter that is up to 3.3V input. 
If you want to pipe it into a Line Input, 
just use a 1uF blocking capacitor in series.
