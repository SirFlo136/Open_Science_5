Welcome to the detailed instructions of group 5. For the time being, we will document everything we did each day in this
file such that we can find it whenever necessary.

### Printing the prototype.
In this section we will carefully describe what we did to print our prototype. 
  - The first thing to do is to watch the youtube tutorial of Lili's protolab, you can find the link to the video
    in the Documents map of this repository. This is a pretty manual for the 3D-printing in the protolab. In order to speed
    things along, we let one person watch the video, but keep in mind that then only that person knows how to print (if          nobody has prior experience).
  - All .step files can be found in this map. Log in on the computer in the protolab, downloaded the files from github     and put all .step-files on the printing area in the SLICER SOFTWARE. There are eight .step files, they all fit on the area
    together. Place them in a way that there is at least a centimeter between each part, you can see an example of this in Figure 1.
  - Choose the printer and nozzle you want to use. We used the 0.4mm nozzle printer, it is recommended to print at 50% width of the nozzle, which meant that we printed at 0.2mm. Then also ensure that the the material is correctly entered in the program. You can find these settings in the top right corner of the screen as in Figure 2.
  - Check wheter all parts are printing from a broad base to a narrow top. If not, rotate them arount such that they are.
  - If all parts seem to be in order, let the program slice the parts with the button in the bottom right. Double check whether everything is supported and if not, add support. You can check for overhang by checking if a significant large portion is collored blue after slicing (see Figure 3). If so, check whether you can rotate the part better or ensure that support is printed below it in the printer settings of Figure 2.
  - Put the filament you want to use in the printer, we used PLA+, which was already connected to the printer.
  - Clean the printplate with the liquid provided and wipe it of.
  - Send the sliced file to the 3D printer and let it print. Sometimes you need to reaffirm which printer you want to use as in Figure 4, ensure that you choose the same printer as in the settings and send your gearbox directly to the printer.
  - Stay close until the first layer is entirely printed, that way you can catch errors early and restart the printer.
  - After a couple of layers your gearbox should look like Figure 5 (altough it may be in a different color).
  - When the printer is done and cooled down, you can detach the parts from the plate by carefully bending it a little bit. Afterwards you carefully remove the brim .You can use a veil or a little bit of sandpaper to get it of perfectly. Now you are all set to construct the gearbox.




  ### Spinning the plate
    Once the gearbox is constructed, we need to connect the motor to a power source and use the wheel to spin the plate. The following steps will walk you through this process.
    - Connect the two wires of the power source to the connectors on the motor, note that there are no plus and minus size, which goes where doesn't matter.
    - Set the power source to a maximum of 6V to prevent the motor from defecting.
    - Use a provided gearbox holder (or your hand) to spin the big plate by holding the wheel against the side of the plate. If the plate or wheel wobbles too much to stay in contact with the plate, you can try make the wheel roll on top of the plate.

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Screen_of_software.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 1: The screen you should see in the software after adding and distributing all the parts<figcaption>
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Change_printer_settings.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 2: The top right part of the screen, here you can choose the printer settings.<figcaption>
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Overhang.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 3: This menu shows the manner in which specific elements are printed, blue means overhang and thus should be supported.<figcaption>
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Reaffirm_printer.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 4: This menu could pop up (but it does not every time). When it does, choose the printer that you had chosen in your original settings.<figcaption>
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Result.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 5: The printer is printing.<figcaption>
</div>

### Assembling the prototype
In this section we will describe how to assemble the prototype using the printed parts and the specified nuts, bolts and washers

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/dissasembled.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 6: Disassembled gearbox.<figcaption>
</div>

###
  - First take the bottom side, identifyable by two small mounds and hole with two screw holes besides it.
  - Srew two small screws into the screw holes until amost flush, then attach the motor by lining up the holes in the base and giving the screws a final twist.
  - Take the small gear and push it onto the rod sticking out of the motor
  - Thread the 4cm bolts through the two middle hole with the direction of the mounds. The small mound is in the middle and will be refered to as 's' and the big mound as 'b'
  - thread one large gear onto the bolt through's'
  - thread one large gear onto the bolt through 'b'
  - thread one small washer and one large gear onto the bolt through 's'
  - thread one small washer and the gear with a rod onto the bolt through 'b'
  - fit a large washer into the large hole in the top plate
  - thread four 3cm bolt through the corner holes of the top plate and place the plastic sleever over the bolts.
  - Fit the two sides together and screw on the nuts on all the bolts
  - lubricate the gearbox with vaseline for optimal use and enjoyment

<div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/assembled.jpeg" alt="lpl sharing" style="width: 50%;"/>
  <figcaption>Figure 6: Assembled gearbox.<figcaption>
</div>
