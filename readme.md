# Feedback Gardenscpr - for Synthux Audrey II
## Custom top plate and knobs built on top of the Synthux Designer Simple kit

♻️🌲This Feedback Gardenscape is not made by Synthux, but is a diy cosmetic alternative by me jonwtr.

Link to official Synthux page about Audrey ii: https://www.synthux.academy/audrey-ii

### Intro / about
As Audrey is built on top of the Synthux Designer Simple kit, and I had a spare one, I made my own interpretation upon Roey's design using some elements I've been experimenting with: custom 3D printed knobs, lasercutting, landscape elements.
I'm using a design reminiscent of crop circles, of which I thought when hearing the mysterious horrorscape sounds.

![Finished Design Custom Audrey II](/img/FeedbackGardenAudrey_frontsideview.jpg)

### 3D printed parts:
- knobs become trees:
    - I made 3 sizes following the original design
    - printed with a Bambulab 0.2 mm nozzle, high quality setting 2 support layers and auto support.
    - the D shaft is slightly tapered to ensure a strong fit
    - Though all trees are the same model I slightly gave each one a different rotation to ensure a bit of randomness.
- reset / boot buttons

![3D print top](/3Dfiles/treesgrouped.png)
![3D print bottom](/3Dfiles/treesgrouped_bottom.png)

### Faceplate
It is made of two layers of laser cut wood glued together, to make them align perfectly I use the standoffs.
- Grass top layer:
    - this layer has a finish with miniature grass (from e.g. train models)
    - glued on before cutting (woodglue).
    - 2 mm holes for bolts to fit in the hex standoffs.
- The bottom layer of the top plate:
    - cutouts to fit the pots
    - hex cutouts fitting the standoffs
    - mounted on the pots without washers in between;
    - the Daisy top pins are slightly too high therefore there's a cutout to accommodate this.
- 2 holes in both plates to allow two 3d printed T shaped button inserts for reset / boot knobs of the Daisy (they are only held in place by fitting in between)

![cutout daisy](/img/FeedbackGardenAudrey_cutoutDaisy.jpg)
![topview](/img/FeedbackGardenAudrey_topview.jpg)
### Box / case:
As my design is slightly bigger I'm also making this a custom size compared to the original one. Slightly taller and wider.
- Made with [makercase](https://www.makercase.com/#/basicbox) 
- the design and exported svg's are using a 0.12 mm kerf setting:
    - Your laser may need different settings;
    - keep in mind that I added extra holes in the bottom plate for the hexnut bolts;
    - and a hole to fit the usb cable (it goes slightly inside the box)

![makercase settings](/img/makercase_basicboxsettings.jpg)
![makercase kerf settings](/img/makercase_kerf.jpg)

### The SVG was made in Adobe Illustrator
I used one of the available design assets to position everything.
- There are three important layers groups
    - top layer grass
    - top layer bottom
    - box / case (this is the makercase 0.12mm kerf version)
- When importing SVG from illustrator into e.g. Lightburn you might need to adjust the dpi import settings

![illustrator screenshot](/img/FeedbackGardenscprAudrey_illustrator.jpg)
![illustrator screenshot 3D view](/img/Feedbackgardenscpr_design_iteration_illustrator3Dview.png)

### Other remarks
I've already foreseen the addition of a three-way on/off/on for when in the future this might be a handy extra for custom firmware. It's connected to an extra digital pin, ignored by the official code.
There is already code implemented for audio in, I did not foresee this, though it could be added later, but this would need another design, as the top right is already 'full'.

Todo
- Planning a making off-ish video on YouTube
