#Author: Nick 

Qoala-t is a relatively straightforward QC-quantification algorithm developed by Australian psychology researchers (hence the play on Koala and quality). It uses the region-wise volumes and cortical thickness from [[freesurfer_outputs]] and effectively performs some sort of outlier detection. As it is designed to maximize detection of bad scans rather than answer a theoretical question the authors just toss all the brain-features into a supervised model (built with either linear or random forest methods if I recall) and spit out a probability between 0-1 that a scan is good. 

Their github has decent documentation on the theory and practice of using it so for more information look there: https://github.com/Qoala-T/QC

[//begin]: # "Autogenerated link references for markdown compatibility"
[freesurfer_outputs]: freesurfer_outputs "freesurfer_outputs"
[//end]: # "Autogenerated link references"