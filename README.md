# RGB Rotary Encoder

## v2 notes: What has changed?
I've added support for these awesome RGB Rotary Encoders, sold by "CN Futai Switches": https://www.aliexpress.com/item/1005002478550056.html
They have a PWM controllable LED inside the encoder, so we get **even more light**, just because we can :)
I also had to adjust some silk screening, including Adams logo, as I needed the space for the 2nd pin header :/ But I did my best to at least keep his logo and brand name!
There's also a 0805-size resistor on there now, as the switch either operates on 3v3, or on 5V with a current limiting resistor. You can basically pick whatever value you want, I picked 200R and it works nice. The higher resistance, the lower the brightness.

![encoder](/images/rgb-encoder.jpeg "RGB Encoder")

## What is this?
This is a super-overkill rotary encoder. Not only does it encode in a rotary fashion, it also lights up! It includes a ring of 20 ultra bright and even more ultra tiny Neopixel LEDs. Ever have trouble deciding between different LED colors? Well here you don't have to. Add this to your next project to give it a brilliant flare in whatever color, or combination of colors, you want.

## How do I use it?
Check out the example code in this repo. The provided examples are for use with a Teensy, but it can be used with any controller that can run Neopixels and read an encoder.

![encoder animations](/images/rgb-encoder-animations.gif "RGB Encoder Animations")