# datacleaning
These are examples of varous scripts (mostly bash and unix tools) I've created for data reductions of daily observations from the HET telescope.

jobsplitter = tool to take a list of executable commands and split the commands efficiently as defined to optimize scheduling not the TACC supercomputer

makedetectcat = script to execute detection algorithms then generate catalogs for each shot 

makelinecat = script to take an input list of objects defined by their RA,DEC,RADIUS,WAVE and extract the line flux and spectrum in the defined aperture and defined location and wavelength. It automatically matches the output catalog format to the input catalog format

reduceonenight= allows a user to enter the DATE and then reduces all nightly data and performs astrometry fitting for the night

reducesetup = for batch processing. This generates all the scripts for an input dateless

reducetwilight =  batch process of twilight frames for a given input date list

reducescience = batch processing of all science frames for a given input date list
