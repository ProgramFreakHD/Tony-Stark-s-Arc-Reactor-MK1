# LED assembly for the glow ring.

## Soldering of the glow ring

The glow ring requires 10 white LED's soldered in a circular ring shape, The 10 LED's have to be soldered in parallel config, meaning plus is soldered to plus and minus is soldered to minus all around the ring, that way a 3.3V supply can power them all.

Now for some and many, it might be dificult to solder 10 leds in a circle by freehanding it, well, not wo worry, I have included a jig for you to print and use, it allows you to mount the LED's in a upright possiston for a better and easy solder job, and also allows you to solder them in a circular ring shape.

The jig is included in the Thingiverse Repo!

![alt text](https://github.com/ProgramFreakHD/Tony-Stark-Arc-Reactor-MK1/blob/main/Pictures/Real%20Life%20Pictures/2021_02_23_18_40_IMG_1695.png)
![alt text](https://github.com/ProgramFreakHD/Tony-Stark-Arc-Reactor-MK1/blob/main/Pictures/Fusion%20360%20Pictures/Transparant%20Background/NVIDIA_Share_iF2AldNYLl.png)

## Wire wrap and mounting

Insert the Led ring you just finished soldering into the transparent glow ring print, from there, you need the 10pcs wire brackets and some enameled copper wire. Don't forget to solder a pair of enameled copper wire to the led ring to provide power to the ring.

To obtain the enameled copper wire, you can find meters worth of copper wires in some old transformers, or just buy some enameled copper wire from the web.

To keep the copper wire from unwinding itself after a wrap, the best and easiest way I found is to scrape the enameling of the wire and solder the wires together for a secure fixturing.

![alt text](https://github.com/ProgramFreakHD/Tony-Stark-Arc-Reactor-MK1/blob/main/Pictures/Real%20Life%20Pictures/2021_02_23_23_43_IMG_1699.png)
![alt text](https://github.com/ProgramFreakHD/Tony-Stark-Arc-Reactor-MK1/blob/main/Pictures/Real%20Life%20Pictures/2021_02_23_23_45_IMG_1700.png)

# Power supply for the LED's

To power the LED's a 3.3V power source is required for the LED, for my arc reactor I used 5V to 3.3V mini boost & buck low noise regulated DC/DC converter, that way I can supply 5VDC from an USB cable to power it.

Some advantages of using buck converter is that it gives you a voltage leeway if let's say for example you connect a 12V supply by accident, that way you don't fry the 10 LED's inside the ring, also the second advantage is that it gives you the opportunity to use 3.7 volt lithium ion battery for the power supply beacuse the converter is both step up and step down, again.

**The arc reactor is not designed to run of 12V so don't even try with my method unless you have taken proper voltage factor and accounted for the 12v Supply!
