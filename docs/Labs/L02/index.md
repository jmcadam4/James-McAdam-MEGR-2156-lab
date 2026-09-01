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

**Prusa Slicer: Grumpy Cat -> Lego Brick**

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="Prusa slicer buildplate.png" alt="buildplate" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="Prusa Slicer Side Panel.png" alt="export panel" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>

When I went on printables.com, a little grumpy cat popped out at me. You can find it <a href="https://www.printables.com/model/1279051-grumpy-cat-figurine">here</a>. I had to have it, so I downloaded it as an STL and brought it over to the prusa slicer. Once it was there I scaled it to roughly 1"x1"x1" and set the print layer height to .15 mm to get some of the fine details into this small of a part. Looking at the first layer surface, I decided it didn't need supports. The angles weren't bad layer to layer and with such a small part, supports sometimes do more harm than good. This print will take 28 minutes and use 283 grams of filament. I had to go back in and change the filament from PLA to PETG, even though that change is not reflected in the images above it is in the file.

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="prusa bed lego.png" alt="buildplate" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="Prusa Settings Lego.png" alt="export panel" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>

<img src="export button.png" alt="export" style="width:50%; height:auto; display:block; margin:1em 0; border:1px solid rgba(0,0,0,.12); border-radius:4px;">

Unfortunately even with these changes, the print time for my group of three was too long so we decided to print pieces of a Lego snail instead. Joel Holder was our slicer, we sent him our files and he sliced it to go to the printer. I found this 2x1 lego brick on printibles.com, clicked the download button, and sent it his way. We left almost all of the settings as they were for this print apart from adding one wall (total of three) and changing the layer height to .2 mm on high speed mode. 

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="lego listing.png" alt="lego listing" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="download lego.png" alt="download lego" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>


I've replicated the slicing process on my computer to show how it went. It's almost entirely the same as my previous part, still no supports and still PLA. These three pieces have a print time of 18 minutes now, much more manageable within a class period. This design had the added benefit of not needing to scale down as they were small enough. The best build orientation for them was sitting with the open end down. This seems counterintuitive but in order for the pieces to snap together, we needed a good quality finish on the top, not the bottom. Now that the settings are in order, we downloaded it using the export g code button shown above.

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="Print temp.jpg" alt="print temp" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="First Layer.jpg" alt="first layer" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>

Now that we had our g-code, we were ready to print. We took the usb thumb drive over to the Prusa, plugged it in, and pressed print. The most important part of the print is often the first layer so it was a massive sigh of relief when it printed well. I didn't get good pictures from the print we did in class as I got swept away in conversation with an instructor talking about the other additive manufacturing lab's 3d printers and their capabilities so I reprinted the legos at home in order to show how it went in this writeup. The images above show the print bed and extruder temps that were used as well as what a good first layer looked like for this part.

<video
  src="lego timelapse.mp4"
  poster="First Layer.jpg"
  controls muted loop playsinline
  preload="metadata"
  width="960">
  Your browser doesn't support HTML5 video.
</video>

From there it was time to let the print run. I took a timelapse of my print at home, I had a slightly incorrect part cooling fan speed so the top layers with no supports printed somewhat poorly in the video, however they were much smoother during our in lab print so supports were indeed not needed with a well calibrated printer. 

<img src="lego full bed.png" alt="full bed" style="width:50%; height:auto; display:block; margin:1em 0; border:1px solid rgba(0,0,0,.12); border-radius:4px;">

It took just minutes to get these parts made and costs about 15 cents when paying retail prices for filament. 3 bricks at 5 cents a piece leaves a nice margin with an average brick in a set costing 15 cents itself. With a full plate of 2x4 flat pieces, it would take 5 hours and 33 minutes to print 98 pieces while using 115 grams of filament. Assuming you're using high quality PLA filament at 20 dollars per kg, the per unit cost would be 2.3 cents. With a 10 cent profit margin at the low end (not 12.5 cents using the previously mentioned 15 cent price because of electricity and maintenance expenses), this part would make lego $1.78 per hour and return parts with little to no post processing needed. If print bed swaps were automated and they ran around the clock, a Prusa Core One would pay for itself in just three and a half weeks. Compared to a mold this is still not as efficient for a corporation as large as lego but it shows you that 3D printed parts are nearing viability for small bath production.

<div style="display:flex; gap:12px; align-items:stretch; margin:1em 0;">
  <img src="lego side.jpg" alt="lego side" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
  <img src="lego top.jpg" alt="lego top" style="flex:1 1 0; min-width:0; height:340px; object-fit:contain; background:#f5f5f5; border-radius:4px;">
</div>

Once all is said and done, we had final parts come off of the printer ready for use. You can see there are some small imperfections but it is good enough for this test with small print speed adjustments needed to get it perfect.



