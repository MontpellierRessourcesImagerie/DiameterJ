# DiameterJ
ImageJ or FIJI plugin for Analysis of images for fibers 

# Getting Started
Download [Fiji](http://imagej.net/Downloads) (latest version). 
 
[Download](https://github.com/MontpellierRessourcesImagerie/DiameterJ/releases/download/v0.19/DiameterJ.zip) and unzip the files and move or copy the three folders into the plugins folder of ImageJ/FIJI.  
 
Restart ImageJ/FIJI after that.  

Run ``DiameterJ Segment`` from the menu ``Plugins/DiameterJ``. Select the input folder containing you images. When the segmentation is finished, select the good segmentation results from the output folder and copy them to a new folder. Then run ``DiameterJ `` from the menu ``Plugins/DiameterJ`` and choose the folder with the selected segmentation results as input folder.

# Known Problems

Combining analysis results from multiple images is currently not working, so you must answer "no" to the last question on the DiameterJ-dialog.
