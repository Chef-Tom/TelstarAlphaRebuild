# TelstarAlphaRebuild
Replacement Mainboard for the Coleco Telstar Alpha Pong Clone
Reuses the chips, switches, and pots from the original board.  Working on sourcing replacements.


<B>Based on the work of Dave Plummer</B>

I had recovered a Coleco Telstar Alpha and saved it from the trash.
This 1977 beauty was a cost reduced version of the Coleco Telstar.  It offers Tennis, Hockey, Jai Alai, and Handball.  (Jai Alai is the 1 Player Practice Mode).
I tried to do a cleaning and minimal restoration without modifying it too much, but the RF Modulator just wasn't putting out a good signal anymore.
As a big fan of Dave Plumer's videos, I had watched his video on using the vintage Ay-3-8500 chip to build a modern version of the console in the case of his original Coleco Telstar.
But the Alpha had a very different design.  It was cost reduced, and all the components are attached directly to the board.  The original used a lot of connectors and some daughter boards.  Finding the exact positions took a few iterations, but now I have a working prototype.


# Version History
V0.1 - I got the hole right for mounting and the switches pretty close, but the holes were all just a little off.
V0.2 - I enlarged the holes for the selector switches which allowed them to sit more properly.  I also adjusted the reset switch design to use either the original or a new switch.
<B>V0.3</B> - Final adjustments to the holes for fitting.  This is the final version that you see in my YouTube video.  This version has a SMT DIP Switch on the back that allows for using either the internal speaker or an internal RCA audio jack (for potential HDMI output).  The RCA jack still needs some work.  I may need some help there.  The SMD dip switches can also just be bridged, and I may switch to bridges or jumpers going forward.   This was mostly for testing and diagnosis.

I didn't realize that I didn't 

Upcoming mods:
 - Fix RCA Audio Output
 - Find a better HDMI converter (current one takes too long to lock on the SYNC signal)
 - Add 9V Liner Regulator?  Doesn't seem necessary but the current power supply is giving 9.56 and I'm not thrilled with that, even though the chip can take up to 12V nominal.
 - Print the V1.0 board in Yellow with Black Silkstreen to feel more like the orange 1 sided board it's replacing.

