# Title
### 3D segmentation and analysis in free (Imagej / ICY) and commercial (Huygens / Imaris) software.

## Aims
Take existing knowledge of 2D image analysis and apply to 3D data sets 

## Target Audience
You’ve done a Fiji course.

## Learning outcomes
Apply knowledge of 2D analysis to 3D data sets
Employ 3D ROI manager to measure 3D objects
Demonstrate 3D analysis with 3D rendering (ICY)

## Duration 
2 hours

## Content
Image histograms and segmentation. Image stack histogram vs single slice histogram.
Demo, threshold a 3D Image using stack / slice histograms.
Why are dim slices incorrectly thresholded?
10 minutes.

Fiji 3D manager
Lecture 10 minutes.
* It has 3D filters, 3D binary operations.
* 3D ROI manager. Measurements, ROI overlaps / colocalization.
* Try it 5-10 minutes.
* Try it: take a binary microglia image and add to 3D manager. Make measurements.
* Try it: take an unprocessed microglia image and add to 3D manager.
* Discuss: Why did it fail? How to improve it.

Commercial software
* Lecture 5 minutes:
* Imaris. Show surface thresholding, more successful than unprocessed in 3D manager.

Lecture 15 minutes.
* Pre-processing in 3D
* Deconvolution (Huygens / ICY?)
* Pixel vs Voxel. PSF, resolution, sampling. 15 mins lecture.
* Pre-processing 3D in Fiji
* 2D processes work in 3D stacks!
* Remove outliers, gaussian or median filters. 
* Binary operations, opening / closing / fill holes.

Exercise (1 hour)
* Take a 2 channel image (Glia and synapses), process and segment each channel in 3D. 
* Measure cell number, volumes (other stuff?).
* Measure synapse numbers, volume.
* Identify synapses overlapping glia cells, measure these.
* Generate an image stack showing original channels plus thresholded glia, synapses, overlaps.
* Make a 3D movie

Future work
* Make the image pretty, colour each cell differently.
* Make a macro (one is provided)
* How to deal with the results? Excel. R. Matlab.
