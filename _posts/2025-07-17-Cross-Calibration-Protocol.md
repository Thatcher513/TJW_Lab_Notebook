layout: post
title: Cross Calibration Steps
date: '2025-07-17'
categories: Protocol
tags: []
## Tips for Proper Cross Calibration of Probes.
1. Regularly automatic calibrate pH Probes and Conductivity probes in apex 
   For pH use a high standard apex calibration. This utilizes pH 7 and pH 10 buffers.
   For the conductivity probes use 53 ms/cm standard 
2. Ensure the conductivity probes are set to ms/cm measurements.
3. Once probes are calibrated through Apex place all probes in regular seawater for 24hours
   This allows us to see if the calibration holds and if any probes are consistently off.
4. Based on 24 hours in saltwater Choose a probe as your reference
   This should be the most accurate probe for both conductivity and pH.
5. Create a range of measurements of known standards.
   Place all probes in DI water(30mins) conductivity should read zero or close to zero.
   Place all probes in Regular Seawater 35ppt (30mins)
   Place all probes in 53 ms/cm standard (30mins)
   Place all Probes in 80ms/cm standard (30mins)
6. Run data in Apex Calibration Script
   [Script](https://github.com/hputnam/Pacuta_Polyp_Bailout/blob/main/Scripts/Apex_Extraction.Rmd)
   Make sure to note and find the times of when you subjected all probes to DI to 80ms/cm
   
   
   