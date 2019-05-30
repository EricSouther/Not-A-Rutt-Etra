# Not-A-Rutt-Etra
Open source project witht he goal of making a simulated Rutt/Etra simulation in TouchDesigner.

I've played with every simulator of Rutt/Etra that is readily available and have seen a real one in person thanks to Matthew Schlanger. Most if not all software only get to the aesthetics of a Rut/Etra with luma-diplacment on the z axis. When Jason Bernagozzi and I made the Signal Culture app Re:Trace, we for a moment joked about calling it Not-A-Rutt-Etra (RIP Bill Etra & Steve Rutt). The joke was made with the understanding that most of the Rutt/Etra simulators don't get close to the functionality and capabilities of an actual Rutt/Etra (including Re:trace).  Today I made some headway with the use of a simple object in TouchDesigner called "scan" that turns a video signal into 5 oscillators, X, Y, R, G, B. This by no means is perfect, but it's getting closer to what a Rutt/Etra and Jones Raster does, by treating video as a signal~ I use the x and y oscillators from the video for x & y SOP and r for the z, which does the iconic 3D displacement. I plan to further develop the process this summer. If your interested let me know, I am open to collaboration.

Reference:
Benton Rutt Etra Walk Through circa 2008 https://vimeo.com/98999296
Bill Etra on Rutt/Etra Video Synthesizer https://www.youtube.com/watch?v=hdL7teOKdtg
BIll Etra Language Lifework (5 minute) https://vimeo.com/61152072 - Benton C Bainbridge

Rutt/Etra Software
Signal Culture Re:Trace http://signalculture.org/retrace.html#.XPArF9NKjUI
Vade: http://v002.info/plugins/v002-rutt-etra/
Mathew Ragan: https://matthewragan.com/2014/04/27/inspired-by-rutt-etra-touchdesigner/
