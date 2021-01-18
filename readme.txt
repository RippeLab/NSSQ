Supplementary software to
Light-induced transcription activation for time-lapse microscopy experiments in living cells
Imaging Gene Expression, 2019

These supplementary materials contain the Nuclear Spot Segmentation and Quantification (NSSQ) package for R (dependent on EBImage), example data and scripts that show how to use the NSSQ functions to analyze image time series of optogenetic reporter gene induction.

Steps to analyze the example data:

(1) Install R, RStudio and the packages EBImage, plyr. ggplot2 and NSSQ.
(2) Set the paths to the data and the results data folders in all four R scripts.
(3) Open the PickCells.R script and run it to manually select nuclei that are to be analyzed.
(4) Run the SegmentTrackQuantify.R script to analyze the image series for the selected nuclei. You can run this script on a computer cluster to speed up the processing. Results can be found in the result folder.
(5) Quality control: Run the AnnotatCells_v1.0.R script to annotate the processed nuclei time series in the RNA channel as good, bad, prerecruited or not induced.
(6) Summarize the good results and create plots using the SummarizeResults.R script.

In order to adapt the segmentation, tracking and quantification to the settings of your experimental data adjust the parameters in the head section of SegmentTrackQuantify.R script.