# CVAV
ColecoVision Audio/Video (CVAV) "Stealth" TRRS Composite Board

License

Please feel free to make and distribute these to whoever you want. Give them away, sell them, make modifications -- I don't care. I made this for myself and if someone else finds it useful, then great. If you don't like this, I don't care. Go make something better and give it to the community. This board definitely works on the 3 ColecoVisions I own; your mileage may vary. Good luck and have fun!

Background

Back in the 1980s, I was an Atari 2600 kid and was always jealous of my friend's ColecoVision; games like Donkey Kong and Time Pilot looks and played "like the arcade." I recently picked up a ColecoVision to add to my collection of vintage consoles, and immediately began looking for a way to add composite video mostly just to clean up the signal over RF. All of the solutions I found included drilling holes in the case for the RCA jacks. Since I'm one of those weirdos that does not like permanently modifying the outside appearance of the console, I wanted a "better" solution. 

The Solution

Using a multi-signal jack in place of a single RCA connector is nothing new, and since all I needed was a wire for composite video, a wire for audio, and ground, the 3.5mm TRRS - or tip, ring, ring, sleeve - jack was an obvious solution as it provides 4 conductors. This particular design replaces the RF modulator board inside the ColecoVision with a new board that provides composite video and audio output over a TRRS jack that is in the exact same spot as the original RF RCA connector. Once installed, you simple plug in a TRRS to RCA cable and away you go.

Building the CVAV

The CVAV is all through-hole components and very easy to solder; probably a 2 of 10 in difficulty. Some of the pads are small and close together, so use a fine tip on your iron. The hardest part is getting the old RF board out of your ColecoVision!

Here are the steps:

(1)	Open up your ColecoVision. This can be trick, but there are lots of guides online to do this safely without damaging anything. Take the main PCB out, pop the lid on your RF can and set it aside.

(2)	Using solder braid and wedge tip on your iron, remove the solder from the bottom of your ColecoVision where the RF can is connected to the main board. Take your time. Wick up all that stinky solder. Use a fume extractor. Listen to some music.

(3)	Use more solder braid and your wedge tip and remove the solder from the top of the RF board where it's connected to the can.

(4)	Use even more braid and carefully desolder the 8 pins that connect the RF board to the pin riser.

(5)	Gently wiggle the RF can and PCB away from the main board. Use heat if you need to and take your time. This is not that hard, just be careful. When you're done, you'll have the can and RF PCB separated from each other and the main PCB. 

(6)	If you haven't sourced an LM1889N chip, you'll need to remove this from your RF PCB. You can buy these on eBay, or you can get more braid and wick away more solder to get that LM1889M chip off of the RF PCB. Maybe you are lucky and have a desoldering station. If that's the case, stop complaining and remove the LM1889N.

(7)	Assemble your CVAV board. A fine tip on your iron helps. Note that C4 is optional and that I have been using a jumper (the leg of a resistor) to bridge the holes and the audio sounds great. Sockets for the ICs are optional.

(8)	Place the RF can back on your main board (don't solder it yet) and then carefully place the CVAV into the can aligning the 8 pins onto the riser. Everything should fit nice and neat with the TRRS in the hole where the RF RCA jack was. It won't be centered; the RF jack wasn't. When everything looks good, solder the 8 pins.

(9)	Before continuing, now is a good time test! Carefully plug in the TRRS cable and power, connect to your video display of choice with the composite video and audio, and play a quick game of Smurf Rescue.

(10) Assuming everything looks good, solder the RF can to the bottom of your main PCB, and solder the exposed pads around the edge of the CVAV to the RF can. These are especially important as they provide rigidity when you plug/unplug your cable.

(11) Put the RF can lid back on and re-assemble your ColecoVision. 

(12) E-cycle the old RF board. Go outside and get some fresh air; you've been breathing a lot of solder fumes!

(13) Play some "arcade quality" games on your composite display of choice!
