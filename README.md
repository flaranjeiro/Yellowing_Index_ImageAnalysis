# Yellowing_Index_ImageAnalysis

This script was designed to calculate the Yellowness Index from plastic pellets and it can be applied to any jpg image file. In summary, when you upload an image to the script, all its pixels are analyzed for color. Therefore, it is important to upload pellet images with background removed by photo editors. The software then employs statistical clustering of the color values of each pixel to identify the ten most likely colors in the image, represented in the CIE XYZ color space format. Based on this data, the Yellowness Index is computed by the Colour library, following the formula outlined in the ASTM E131 method. 

For de function to run update the last lines to your convinience.
