# Scioly Balsa Event Autoloader

This is my take on an autoloader used for Bridge, Boomilever, and Tower. It uses an aluminum extrusion frame, a 5 gallon water jug to hold the sand, and some printed parts for the spout.

<div align ="center">
  <img src="/photos/loader side.jpg" alt="Side view of autoloader" width="50%"/>
  <p>Side view of the loader</p>
</div>

# Materials

## Part List

| Part                             | Qty          | Price     | Source                                                                                                                 |
|----------------------------------|--------------|-----------|------------------------------------------------------------------------------------------------------------------------|
| 2020 extrusion                   | See cut list | $112      | [tnutz.com](https://www.tnutz.com/product/exm-2020/)                                                                   |
| 2020 M6 feet (optional)          | 4            | $8        | [tnutz.com](https://www.tnutz.com/product/lf-020-a/)                                                                   |
| 2020 corners + mounting hardware | Min. 36      | $26       | See below                                                                                                              |
| 5 gal. water jug                 | 1            | $16       | See below                                                                                                              |
| 1/2 in. aluminum rod             | 2            | $10       | [Amazon](https://www.amazon.com/dp/B0GJHNZRNZ)                                                                         |
| 2 in. x 12 in. PVC pipe          | 1            | $8        | [Home Depot](https://www.homedepot.com/p/Charlotte-Pipe-2-in-x-2-ft-PVC-DWV-Schedule-40-Pipe-PVC072000200HA/100585960) |
| 2 in PVC 45 deg elbow            | 1            | $3        | [Home Depot](https://www.homedepot.com/p/NIBCO-2-in-PVC-DWV-45-Degree-Hub-x-Hub-Elbow-C4806HD2/100346919)              |
| 2 in PVC flexible adapter        | 1            | $7        | [Home Depot](https://www.homedepot.com/p/Fernco-2-in-x-2-in-DWV-Flexible-PVC-Coupling-P1056-22/100096490)              |
| Set screws                       | 20           | $7        | See below                                                                                                              |
| 3d printed parts                 | See below    | See below | Printer                                                                                                                |
| M5x16 screws                     | 4            | $5        | [Amazon as an example](https://www.amazon.com/dp/B0DGXWZJP2)                                                           |
| Total                            |              | ~$200     |                                                                                                                        |

Extrusion: The cheapest source I could find for cut extrusion was from [tnutz.com](https://www.tnutz.com). If you have means to cut it yourself and have, say, a robotics team that you could steal extrusion from, 

Mounting hardware: I used 44 corner brackets on my final build but unfortunately the cheapest packs on Amazon come as 40 pieces. You can get away with only using 36 brackets, leaving you with 4 extra T-nuts to screw on the rod and pipe holders. [Here](https://www.amazon.com/dp/B0FFMQ9NPP) is a link to 40 brackets, [here](https://www.amazon.com/dp/B0GF89B14F) is a link to 30 with a cheaper unit price that you could get two of to have some extra.

Water jug: This is best sourced locally, most grocery stores carry this. You might be able to find one for less that $16. It should be something similar to [this](https://www.homedepot.com/p/Primo-Primo-5-Gal-Water-with-Empty-Exchange-1008778394/205216096).

Set screws: I happened to have #4-40x1/4" set screws on me, so that's what I designed this around. However, any similarly sized set screw should work. [Here](https://www.amazon.com/dp/B0CY972RP7) is the one I used, but use whatever you have or is cheapest on Amazon at the time.

## Cut List

| 2020 Extrusion Length | Qty |
|-----------------------|-----|
| 30 in                 | 4   |
| 15 in                 | 6   |
| 25 in                 | 4   |
| 20 in                 | 4   |
| 8 in                  | 4   |

If you're looking to install feet and are ordering from tnutz, choose the M6 x 1.0 x 25mm deep tap option on one end when ordering the 30 in extrusion pieces.

## 3D Printed Parts

[Download link](https://github.com/toasoast/SciolyAutoloader/releases/download/v1.0.0/3dfiles.zip)

Printing tips: the spout, shaft collars (you need 2), pipe holder, and rod holder have pretty loose tolerances. Printing the cap and corner in PETG is recommended since these parts experience a torque. The corner can crack if the set screws are overtightened, use more walls than you normally would.

If you want to use different set screws, STEP files of parts with generic 1 mm holes where set screws should go are provided.

The holes on the pipe and rod holders are sized for M5x16 screws (standard T-nut size).

# Assembly

<div align ="center">
  <img src="/photos/loader extrusion.jpg" alt="Aluminum extrusion" width="40%"/>
  <p>tnutz.com order</p>
</div>

<div align ="center">
  <img src="/photos/loader assembly.jpg" alt="Loader assembly" width="40%"/>
  <p>3D model of the assembly</p>
</div>

The easiest way to cut the bottom off the water jug I found was with a standard utility knife. Attach the 45 degree PVC elbow using the flexible coupling.

For the frame, start with general shape, don't worry about the exact alignment. Make sure that you add two T-nuts each to the extrusion in the middle that the pipe holder sits on and to the bottom of the side extrusion that the rod holder hangs under (4 total). See the assembly for clarification. 

The 30 in extrusions are the legs, the 25 in extrusions are the long side, the 15 in extrusions are the short side, the 20 in extrusions are the legs of the jug holder, and the 8 in extrusions are the sides of the jug holder. I assembled the jug holder part separately from the rest of the frame and attached it, but it may be easier to assemble it directly on the frame as getting it into the T-nuts was kind of difficult. The 8 optional corner brackets that I used are the 4 at the top of each leg that connects the two side pieces, and 4 where the jug holder attaches (you can use one corner per leg instead of two).

<div align ="center">
  <img src="/photos/loader frame.jpg" alt="Frame of the loader" width="50%"/>
  <p>Frame mid-assembly</p>
</div>

Once you have the general shape of the frame assembled, drop the water jug assembly in and connect the PVC pipe. Adjust the sides of the jug holder so the top of the water jug is roughly around the same height or below the top of the 20 in extrusions. Slide the printed pipe holder onto the pipe and screw it into the T-nuts using the M5x16 screws. Adjust the extrusions (vertically and horizontally) so that the pipe is naturally resting at 45 degrees.

<div align ="center">
  <img src="/photos/loader incomplete.jpg" alt="Loader mid-assembly" width="50%"/>
  <p>The loader with uncut pipe</p>
</div>

The axle assembly should be done separately. The printed corner takes 12 set screws, the cap has 6, and each shaft collar has one. Assemble the cap, spout, shaft collars, and rod holder onto one of the rods. Tighten the set screws on the cap but leave the ones on the shaft collars loose. Attach the spout to the end of the PVC pipe and attach the rod holder to the T-nuts previously inserted into the frame using two M5x16 screws. Adjust the position of the rod holder on the frame and the position of the extrusions as needed until the rod goes through the spout straight and it rotates freely. Tighten down the set screws on the shaft collars and the screws in the extrusion corner brackets.

<div align ="center">
  <img src="/photos/loader axle assembly.jpg" alt="Axle assembly" width="50%"/>
  <p>The axle of the loader</p>
</div>

<div align ="center">
  <img src="/photos/loader axle.jpg" alt="Axle assembled" width="50%"/>
  <p>Installed axle</p>
</div>

<div align ="center">
  <img src="/photos/loader spout.jpg" alt="Loader spout" width="50%"/>
  <p>Spout of the loader</p>
</div>

Separately, insert the other rod into the printed corner. This rod will act as the handle and should go in the end with 4 set screws. The axle will connect to the end with 8 set screws. Depending on your printer's tolerance, this may be quite tight, I had to use a mallet to install the handle into the corner. Then, you can install the corner onto the exposed end of the axle. Tighten down the set screws (don't overtighten though since they corner can crack!). You should now be able to open the spout with the handle.

<div align ="center">
  <img src="/photos/loader corner.jpg" alt="Axle corner" width="50%"/>
  <p>The installed corner</p>
</div>

Here's some final photos:

<div align ="center">
  <img src="/photos/loader iso.jpg" alt="View of the complete loader" width="50%"/>
  <p>The completed loader!</p>
</div>

<div align ="center">
  <img src="/photos/loader sand.jpg" alt="Loader with sand" width="50%"/>
  <p>Test with sand</p>
</div>

# Credits

Thanks to members of the Balsa Engineering server for idea inspiration and with several design aspects.

Updated August 2026
