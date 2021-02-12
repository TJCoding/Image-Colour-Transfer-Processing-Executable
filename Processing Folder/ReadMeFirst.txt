
INSTRUCTIONS
===========

Click the file "TJColourTransfer2.exe", (but first read the first paragraph of IMPORTANT NOTES below).

An on-screen display will be generated and the file "processed.jpg'" will contain the processed image as derived from the images in "target.jpg" and "palette.jpg".

The processed image (as saved) will intially have a maximum dimension of 640 pixels, but this can be varied by altering the value '640' in the file 'ParameterInputs.txt'.
Other processing parameters may also be modified, if required, as described in that file. 

Different images may be processed by renaming each of the existing "target.jpg" and "palette.jpg" files and adding in new files named as "target.jpg" and "palette.jpg".

Alternatively, if the file "target.jpg" is deleted or renamed, then the program will provide a file selection dialog for the input and output files.

Further details of processing options can be found in the file "ParameterInputs.txt".  


IMPORTANT NOTES
==============

When you first click "TJColourTransfer2.exe", you may get a message "Windows protected your PC". To overcome this, click "More info" and then "Run anyway".
There is no issue here.  Microsoft is being over cautious for software which does not originate from a commercially certified software company. 

The facility to read in files makes use of third party public domain software.  Unfortunately it does have one minor quirk.
It cannot read images from or write images to a base directory.  It requires that the images lie within a folder.
So, for example, images on a USB should not be directly stored on the base storage but should be within a folder.

If the output image size is increased from 640 pixels, then the processing will take longer.  
The program could fail if a very large output image is specified.
A failure will normally be indicated by the display of an error message.
Processing time and image size capacity will be dependent upon the particular computing device.


CHOICE OF IMAGES
==============

I hope you enjoy using this software.

It will produce interesting results for some combinations of input images but not others.

I am always looking for good examples which illustrate the software's capability.

If you find an image pair that works particularly well, you can email them to me with the heading "Colour Transfer Images"
terence.johnson@gmail.com


SOFTWARE DISTRIBUTION
===================

Copyright © Terry Johnson January 01/12/2020
https://github.com/TJCoding
This program is free software. It comes without any warranty, to  the extent permitted by applicable law. 
You can redistribute it under the GNU Lesser General Public License v3.0
OpenCV dlls are distributed under a BSD licence. 

