# Stability Of Strange Dwarfs

This repository contains the code written for my Bachelor's thesis in the Physics Department of Aristotle University of Thessaloniki, titled "Stability of Strange Dwarfs".  
Supervisor: Ch. C. Moustakidis.  
This project marked my first experience with Python and Computational Physics, so while the code is functional, it may not be fully optimized in terms of performance.  
You can access the full thesis for free on the AUTh website [here](https://ikee.lib.auth.gr/record/360475/?ln=en). 


 # 🧠Thesis Objective
The main goal of this thesis was to compute the fundamental eigenvalue of the Sturm-Liouville Stability Problem for Strange Dwarf star configurations to assess their stability.  
The study is based on the following two papers:
* ["On the Stability of Strange Dwarf Hybrid Stars", Alford (2017)](https://arxiv.org/abs/1705.09880)
* ["Possible New Class of Dense White Dwarfs", Glendenning (1995)](https://ui.adsabs.harvard.edu/abs/1995PhRvL..74.3519G/abstract)

# 📁Repository Contents
The files of this repository are:  
* "main.ipynd" - Main script for calculating the fundamental eigenvalue for a given central pressure.  
* "MRPlane.ipynd" - Script to generate the Mass-Radius (MR) plane.  
* "Eigenvalues.ipynd" - Script to plot all computed eigenvalues.  
* "BPS.dat" - Data file containing the Baym-Pethick-Sutherland equation of state. 
* Graphs - Output plots and diagrams from the thesis analysis. 

# 📊Key Results

Equation of State for Strange Dwarf Stars    
![eos](graphs/eos.png)

Mass-Radius Plane  
![mr](graphs/MR_final.png)

Fundamental Eigenvalues vs. Central Pressure  
![eigen](graphs/eigen_plot.png)
![eigencd](graphs/eigencd_plot.png)

 
