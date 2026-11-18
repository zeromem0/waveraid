# Wave Raid

A small side-scrolling game where the land is a signal. DC levels, sines, pulse trains, UART
frames, noise, triangles, ringing and PWM go by from right to left, each named on the top bar the
way a scope would name it ("SINE 1.2 kHz", "UART 9600 8N1"). Your ship flies over them. Shoot what
flies, bomb the chips and the aerials on the signal, and keep clear of the trace.

**Play it:** https://zeromem0.github.io/waveraid/

| PC | Phone | |
|---|---|---|
| arrows | stick | fly |
| Space | FIRE | fire (hold it to keep firing) |
| B | BOMB | bomb |
| A | AUTO | autopilot: holding an arrow takes the stick back |
| P | PAUSE | pause |
| Esc | | back to the title |

You have five ships. A ship is lost if it touches the land, a flyer or a shot.

It first ran on an oscilloscope: the FNIRSI DST-210, in the alternative firmware
[APRE-210](https://github.com/zeromem0/apre-210). This page is the same game, step for step, on its
320 × 240 screen, with its fonts and colour themes.

It is one HTML file with nothing to install. Nothing is sent anywhere; the theme, the sound and your
best score stay in your browser.

MIT licence.
