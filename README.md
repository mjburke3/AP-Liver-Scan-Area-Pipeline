1.	Pipeline is optimized for single-channel RGB TIFF images. Adjust accordingly. 

2.	Update Regex to match your unique image filename for accurate metadata extraction. 

3.	It is recommended to use your own custom absorbance calibrator images for the UnmixColors Module. More information at: https://carpenter-singh-lab.broadinstitute.org/blog/unmixcolors-modules-tutorial

4.	This pipeline uses 3 different methods of automatic thresholding (Otsu Adaptive, Otsu Global, and Robust Background). Use the thresholding approach that produces the most accurate results in the auto-saved QC images. In our study, we chose Robust Background for final data collection.  
