# ADCIRC-WETDRY

This repository is a collection of realistic wetting and drying cases that are problematic for the DG-CG code.
Each mesh directory contains several subdomain files that quickly become unstable during simulation. 

For the purpose of testing,
each subdomain can be run in reasonable time using the serial `adcirc`. 

To plot the output of each subdomain, use https://github.com/namo626/adcirc_subdomain to renumber `fort.14` and then use
the Python interface of FigureGen: https://github.com/namo626/FigureGen/tree/dev.
