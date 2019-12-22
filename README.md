# LEGO.scad

An OpenSCAD LEGO-compatible brick generator.

This parametric brick takes the work of https://github.com/cfinke/LEGO.scad a few steps further, taking the schema closer to being fully-compatible with LEGO bricks. My personal motivation is to make this library suitable for building custom bricks on an SLA printer, to the accuracy of the printing device.

Likely you will need a print at a resolution of 100-microns or finer for the prints to turn out well. 

Changes compared with the cfinke version:

 (1) Added a slight rounding to the studs. This uses a modified version of the code presented by EduardoFoltran in the cfinke comments. 
 
 (2) Slightly changed the dimensions so they are a match for LEGO brick dimensions.  The cfinke version has some measurements that are off by roughly 0.1mm--0.2mm.  
 
Anticipated changes in the near future:

 (1) Add the supporting trusses that appear on the underside of LEGO bricks. 
 
 (2) Hollow-out the underside of studs, as one sees in actual LEGO bricks.
 
