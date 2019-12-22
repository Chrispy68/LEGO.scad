# LEGO.scad

An OpenSCAD LEGO-compatible brick generator.

This parametric brick takes the work of https://github.com/cfinke/LEGO.scad a few steps further, taking the schema closer to being fully-compatible with LEGO bricks. My personal motivation is to make this library suitable for building custom bricks on an SLA printer, to the accuracy of the printing device.

Likely you will need to print at a resolution of 100-microns or finer for the prints to turn out well. 

Changes compared with the cfinke version:

 (1) Added a slight rounding to the studs. This uses a modified version of the code presented by EduardoFoltran in the cfinke comments. 
 
 (2) Slightly changed the dimensions so they are a match for LEGO brick dimensions.  The cfinke version has some measurements that are off by roughly 0.1mm--0.2mm.  

 (3) Began adding the trusses / supportive bracing between the brick walls and
   the posts. Presumably this is not complete yet -- will compare with some of 
   my son's larger bricks.

 (4) Added the recesses opposite studs. 
 
Anticipated changes in the near future:

 (1) Add the supporting trusses that appear on the underside of LEGO bricks. This
  is partially implemented at present. 
 
Printing advice: 

I have been printing on a Formlabs Form 3 this is a resin SLA printer.  
After washing and curing the parts I notice a shrinkage of:

Grey resin -- 0.4% to 0.8%
Clear resin -- 0.9% to 1.5%

So I would advise scaling by a factor of 1.004 in grey, and 1.009 in clear. 
I will update the scaling advice as I gain experience with the process.
