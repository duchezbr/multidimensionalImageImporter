multidimImageImporter_UI:
This GUI uses BioFormats matlab files to import multidimensional arrays (XYZCT) and OME-XML metadata to the MATLAB workspace.

MATLAB is a frequently used programming environment for image processing tasks.  However, importing multidimensional arrays can often be a challenging hurdle particularly for novice users.  This GUI uses Bio-Formats code that is used by default to import multidimensional data in FIJI (FIJI Is Just ImageJ).  Now you can start viewing, processing and analyzing images without devoting time up front to just get image data into your workspace.

 
Getting started:
Sample images can be found with the multidimImageImporter_UI at MATLAB File Exchange (search Author: Brian DuChez).  The documentation embedded above the UI code provides examples for how multidimensional data can be manipulated after importing with multidimImageImporter_UI.  Addtionally, see https://docs.openmicroscopy.org/bio-formats/5.7.1/users/matlab/index.html to download Bio-Format matlab scripts necessary to run this GUI.

1. To start enter multidimImageImporter_UI at the command line of the MATLAB workspace. 
2. Select the file tab then Import on the drop down menu.  
3. Navigate to the image file that you wish to import (the list_box will be populated with metadata for images including the 
series #, X, Y, Z, channel and time dimensions).  If image file 
contains multiple series, each series will be listed seperately.
4. Click on an image in the list_box to import image data directly to the workspace.
The workspace will be populated with a structure (I) containing three fields... 
I.name: name of the image file with XYZCT dimensions 
I.img: image array 
I.meta: OME-XML metadata  
5. Select as many images from the list_box as you wish to be appended to the structure.
6. Select 'Clear' under the File menu to reset list_box menu and start fresh.





