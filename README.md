# KineticAnalysis
Python script for calculating and plotting kinetic analysis of battery materials. Script included is specifically for Lithium Manganese Oxide (LiMn2O4), though can be easily extended to other battery materials by changing the appropriate constants in script.

Script generates CV plots of batteries materials and shifts CVs accordingly to account for peak shifting from kinetic effects during different sweep rates. Script utilizes 0.2 mV/s, 0.5 mV/s, and 1 mV/s sweep rates with CV data collected using a BioLogic VSP potentiostat. From there, the script generates and plots the capacitive portion of the CVs and calculates the percent capacitance.

![0.2mVs](http://postimg.org/image/6c8wdcyut/][img]https://s26.postimg.org/6c8wdcyut/0.2m_Vs.png)

![0.5mVs](http://postimg.org/image/731mj5185/][img]https://s26.postimg.org/731mj5185/0.5m_Vs.png)

![1mVs](http://postimg.org/image/jj2xqmjxx/][img]https://s26.postimg.org/jj2xqmjxx/1m_Vs.png)

![Final Result](http://postimg.org/image/ygbermx6d/][img]https://s26.postimg.org/ygbermx6d/Final_Kinetic_Analysis.png)
