# KineticAnalysis
Python script for calculating and plotting kinetic analysis of battery materials. Script included is specifically for Lithium Manganese Oxide (LiMn2O4), though can be easily extended to other battery materials by changing the appropriate constants in script.

Script generates CV plots of batteries materials and shifts CVs accordingly to account for peak shifting from kinetic effects during different sweep rates. Script utilizes 0.2 mV/s, 0.5 mV/s, and 1 mV/s sweep rates with CV data collected using a BioLogic VSP potentiostat. From there, the script generates and plots the capacitive portion of the CVs and calculates the percent capacitance.

Example plots:

![Example 0.2mVs](https://user-images.githubusercontent.com/17757035/29955644-ef518d1a-8e95-11e7-93d0-3f98f26978d3.PNG)

![Example 0.5mVs](https://user-images.githubusercontent.com/17757035/29955643-ef4ea974-8e95-11e7-905c-9315b90bd436.PNG)

![Example 1mVs](https://user-images.githubusercontent.com/17757035/29955642-ef4cbce0-8e95-11e7-9016-22a4f4f16be1.PNG)

Final result with calculated capacitance and plot:

![Final result with calculated capacitance and plot](https://user-images.githubusercontent.com/17757035/29955645-ef54c5fc-8e95-11e7-8d5f-c1714f4d59ae.PNG)
