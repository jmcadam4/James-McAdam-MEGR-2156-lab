# L2 – Print Something Small

**DfAM Consideration**

FdAM requires minimal overhangs and ideally a flat surface to print off of. Overhangs, at the least, slow the print down and at the worst they can cause failures and stringing. Flat surfaces ensure proper bed adhesion and a solid first layer.

Source: <a href="https://chateletusa.com/pages/design-for-additive-manufacturing?srsltid=AfmBOor72hsCoAdfF4PYLkn-TY1_A2-mfuZrSsL8z1z4MwXsIdBwqf0z">Chatele USA</a>

**FDM Consideration pt. 2**

Infill vs Walls

Many people opt to increase infill alone when trying to make stronger prints. This sounds right intuitively however a part of the configuration that is sometimes overlooked that helps greatly to achieve this goal is wall loops. 2 walls is sufficient for casual prints, 3-4 for watertight or strong prints, and sometimes more if you need extra strength. Increasing wall loops will often strengthen the product more per additional gram of filament than infill, sometimes it can be up to two times as efficient.

Source: <a href="https://www.snapmaker.com/blog/3d-printer-wall-thickness/">Snapmaker</a>

**Teammate Research**

A lot of materials have entered the market over the last few years, while it's still limited to plastics and plastic fiber blends for the most part, there are a lot to choose from. Looking into product requirements allows you to see what filaments are viable.

**Prusa Slicer: Grumpy Cat**

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="Prusa slicer buildplate.png" alt="buildplate" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="Prusa Slicer Side Panel.png" alt="export panel" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>

When I went on printables.com, a little grumpy cat popped out at me. You can find it <a href="https://www.printables.com/model/1279051-grumpy-cat-figurine">here</a>. I had to have it, so I downloaded it as an STL and brought it over to the prusa slicer. Once it was there I scaled it to roughly 1"x1"x1" and set the print layer height to .15 mm to get some of the fine details into this small of a part. Looking at the first layer surface, I decided it didn't need supports. The angles weren't bad layer to layer and with such a small part, supports sometimes do more harm than good. This print will take 28 minutes and use 283 grams of filament. I had to go back in and change the filament from PLA to PETG, even though that change is not reflected in the images above it is in the file.
