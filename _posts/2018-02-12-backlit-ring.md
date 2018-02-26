---
layout: post
title:  "Making a pcb for a backlit ring"
author: Joseph Lundy
thumbnailpath: /img/backlit-ring/[INSERT_FILE_NAME].jpg
---

We've been designing a pcb to make a backlit wearable, for better finger tracking in varying lighting conditions.

##### First board - poorly manufactured 

Getting a PCB made at E5 proved easier said than done.  Our first board had a lot of issues.  First, they did not have material for providing soldermasking.  Second, the silkscreen was complete fiasco, with paint everywhere on the board, including conductive pads.  Needless to say, we needed it re-printed properly.

<img src="/img/backlit-ring/v1-top.jpg" alt="the top of a 1 inch by 1 inch copper PCB, with white paint covering its surface.  It has pads for resistors and leds" class="img-responsive" />
<p>PCB - top</p>
<img src="/img/backlit-ring/v1-bottom.jpg" alt="the bottom a 1 inch by 1 inch  copper PCB, with white paint covering its surface.  It has pads for a battery holder" class="img-responsive" />
<p>PCB - bottom</p>

##### Second board - poorly designed, with manufacturing defects
For the second board, we had it printed without a silkscreen.  Unfortunately at the time the E5 facility still couldn't provide soldermasking.  Nevertheless, we attempted to solder on components.  This proved very difficult, since our resistor and leds were very small.  We were able to solder the resistors and leds, but the battery holder was too tricky to solder, and the lack of soldermasking resulted in solder getting stuck all over the board.  We also realized that the vias were defective.  Back to square one.

<img src="/img/backlit-ring/lior-soldering.jpg" alt="" class="img-responsive" />
<p>Lior with surgeon-like hands patiently solders a miniscule resistor to the board</p>

<img src="/img/backlit-ring/v2-top.jpg" alt="the top of a 1 inch by 1 inch copper PCB. It has resistors and leds soldered onto it" class="img-responsive" />
<p>The end result - top</p>

<img src="/img/backlit-ring/v2-bottom.jpg" alt="the bottom a 1 inch by 1 inch  copper PCB.  It has a battery holder soldered onto it" class="img-responsive" />
<p>The end result - bottom</p>


##### Third board - a new hope
For our third board, we bought larger, 1206 sized resistors, and made the pads for everything larger.  As well, we used a more suitable plastic battery mount, that provides much better insulation for the battery, and easier-to solder contacts. We also replaced the vias with larger plated through-holes.  Finally, the E5 facility was able to print it with solder masking. This new board should be much easier to hand solder, and hopefully we can use it to due more in depth testing in different lighting environments.
<img src="/img/backlit-ring/v3-top-switch-battery.jpg" alt="the top of a 1 inch by 1 inch copper PCB. It has green insulation on it, with large exposed copper pads for soldering leds and resistors." class="img-responsive" />
<p>PCB V3 - top</p>

<img src="/img/backlit-ring/v3-bottom-switch-battery.jpg" alt="the bottom of a 1 inch by 1 inch copper PCB. It has green insulation on it, with large exposed copper pads for soldering a battery mount." class="img-responsive" />
<p>PCB V3 - bottom</p>
