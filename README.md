## About OoTText2PNG
OoTText2PNG is a tool generate images to use with [retro](https://github.com/HarbourMasters/retro), it will automatically generate images for various game elements used in [Ship of Harkinian](https://github.com/HarbourMasters/Shipwright)

## How to install
Just extract and run ****OoTText2PNG.exe****

## Using OoTText2PNG
Using OoTText2PNG is fairly straight forward, simply select an element to adjust font, size, outline, bold, italic and underline from a tab. For more fine tuning options such as offsets click on the options button in the toolbar. You can also cycle through example text by clicking left mouse to go forward and right mouse to go back. To generate images from here check all elements you want to generate image for and select an output directory and press ****Generate Images****. Once that is done you can then use [retro](https://github.com/HarbourMasters/retro) to create your OTR file for use with Ship of Harkinian.

## Adding Images
You can also specify a PNG image to include on generated images by either clicking on the image button on toolbar or in options. This is an option if you want to include extra graphical elements. PNG image resolution used here should be ****DOUBLE**** your intended resolution for any specific element when using this option.

## Font Images
Since this is a beta and will remain so until project is migrated to C# do not expect perfection from font generation just yet. In most cases it produces decent results but it will obviously depend on font, size etc. Offsets have been calculated for most characters that need them (all alphabetic etc) but may still require fine tuning too.
Other characters have not been tested yet. If you want to see which characters have offsets you can checkout the Google sheet [here](https://docs.google.com/spreadsheets/d/1yimCZf6W96utbVUSrPGpt-VSJLFvEX40PjsNfMGKPO0/edit?gid=36852122#gid=36852122). Offsets are calculated on 64x64 character size based on 1080 vertical resolution. -1 is not tested, 0 is no offset needed and any number is an offset, either left or right.
Button characters (A, B, L, R, Z and C buttons) are automatically generated however they have not been tested how they look in the game yet. No solution for final two characters (target and control stick) as yet but images will still be generated which you can edit manually for now.

## Known Issues
Currently diacritics for French and German do not render correctly. A solution for this is in the works.

