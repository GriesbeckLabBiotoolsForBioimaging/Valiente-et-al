# Acquisition
The file acquisition works controlling the imaging set-up previously described by Fabritius, A. et al. in the article  "Imaging-Based Screening Platform Assists Protein Engineering. Cell Chem Biol 25, 1554-1561 (2018)". 
This script was adapted for acquiring images over time using only the green channel for exciting the mNeonGreen based indicators. 
The output is a numpy file for each plate which is identified for further picking if necesary. 
Normally, two images were acquired before adding calcium and then four additional images were acquired. 

# Analysis
The analysis script file uses the same structure described in Fabritius et al 2018, but incorporating the time-lapsed scheme. 
In this case, it not only measures the fluorescence values for each colony but also the response, which is calculated using the first and last picture. 
An example numpy file (colony plate) is provided. The files transformation.pyc and analyzed.pyc are necesary for executing the analysis script and are also provided.   
