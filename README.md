# segmentation_membrane
getSegmentation takes the image of cell membranes and returns its segmentation. Since segmenting the entire image can be challenging, the segmentation is done incrementally over a smaller window that moves across the whole image. The other two arguments, stepsize and windowsize, are how many pixels the window moves in each step and the size of the window. The default values are 20 pix and 100x100 pix. 

