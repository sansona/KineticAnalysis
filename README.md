# KineticAnalysis
Python script for calculating and plotting kinetic analysis of battery materials. Script included is specifically for Lithium Manganese Oxide (LiMn2O4), though can be easily extended to other battery materials by changing the appropriate constants in script.

Script generates CV plots of batteries materials and shifts CVs accordingly to account for peak shifting from kinetic effects during different sweep rates. Script utilizes 0.2 mV/s, 0.5 mV/s, and 1 mV/s sweep rates with CV data collected using a BioLogic VSP potentiostat. From there, the script generates and plots the capacitive portion of the CVs and calculates the percent capacitance.

<br>
<img height = "500" src ="https://github.com/sansona/KineticAnalysis/tree/master/Images/0.2mVs.PNG">
<br>

<br>
<img height = "500" src ="https://github.com/sansona/KineticAnalysis/tree/master/Images/0.5mVs.PNG">
<br>

<br>
<img height = "500" src ="https://github.com/sansona/KineticAnalysis/tree/master/Images/1mVs.PNG">
<br>

<br>
<img height = "500" src ="https://github.com/sansona/KineticAnalysis/tree/master/Images/FinalKineticAnalysis.PNG">
<br>
