Welcome to the detailed instructions of group 5. For the time being, we will document everything we did each day in this
file such that we can find it whenever necessary.

## Wednesday 23 september
So the first thing we had to do today was find our groups. For the group reproducing our efforts this should not
be such a big problem because they already did the arduino project together.

First we cloned the entire repository to one of our own, and added everybody as a collaborator. If you do not 
know how to do this, googling this gives a fairly straightforward guide.
Afterwards we carefully read the README.md document providing the original explanation and looked through all the files.
We noticed a couple of things:
  -  All the .step files needed to make the gearbox are already included. This means that we do **not** have to create 
     our own gears, but rather can use these files to print our first prototype.
  -  As mentioned in the README, there is a picture of the gearbox under the 'results' section. We can use this to get
     a feeling for the way the gearbox should be constructed.
  -  We think that the final goal of the project is to create a gearbox that rotates at an 8-to-50 ratio.

### Printing the prototype.
In this section we will carefully describe what we did to get our prototype. 
  - The first thing to do is to watch the youtube tutorial of Lili's protolab, you can find the link to the video
    in the Documents map of this repository. This is a pretty manual for the 3D-printing in the protolab. In order to speed
    things along, we let one person watch the video, but keep in mind that then only that person knows how to print (if          nobody
    has prior experience).
  - All .step files can be found in this map. We logged in on the computer in the protolab, downloaded the files from github     and put all .step-files on the printing area in the SLICER SOFTWARE (I do not know the name of the app). There are eight     .step files, they all fit on       the area
    together. Place them in a way that there is sufficient distance between them (like a centimeter).
  - Choose the nozzle you want to use. We used the 0.4mm nozzle printer, it is recommended to print at 50% width of the         nozzle, which meant that we printed at 0.2mm. Then also ensure that the the material is correctly entered in the program/
  - Check wheter all parts are printing from a broad base to a narrow top. If not, rotate them arount such that they are.
  - If all parts seem to be in order, let the program slice the parts. Double check whether everything is supported and if       not, add support. You can see this when after slicing, parts are blue (overhang) and check whether below it, green is printed (support). We also added a brim. It seems as this is not necessary but just to be sure that parts would not fall      down we did.
  - Put the filament you want to use in the printer, we used orange PLA+, which was already connected to the printer.
  - Clean the printplate with the liquid provided and wipe it of.
  - Send the sliced file to the 3D printer and let it print.
  - Stay close until the first layer is entirely printed, that way we can catch errors early and restart the printing.
