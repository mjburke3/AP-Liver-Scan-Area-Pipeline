1.	Pipeline is optimized for single-channel RGB TIFF images. Adjust accordingly. 

2.	Results are exported in pixels and should be converted to appropriate units. 

3.	Update Regex to match your unique image filenames for metadata extraction.

4.	It is recommended to use your own custom absorbance calibrator images for the UnmixColors Module. More information at: https://carpenter-singh-lab.broadinstitute.org/blog/unmixcolors-modules-tutorial

5.	This pipeline uses 3 different methods of automatic thresholding (Otsu Adaptive, Otsu Global, and Robust Background). Use the thresholding approach that produces the most accurate results in the auto-saved QC images. In our study, we chose Robust Background for final data collection.  

6.	This pipeline is purpose-built for large, stitched whole-section scans. It incorporates automatic detection of tissue edges and holes (ie. area within large blood vessels). This may be incompatible with high magnification or cropped images. Optimize accordingly. 
