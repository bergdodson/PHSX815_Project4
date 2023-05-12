# PHSX815_Project4
Final Project for PHSX 815

## Goal
Estimate the critical temperature of a magnetic phase transition using 2D Ising model 

# In the write read format:
`PHSX815_Proj4_write.py` will run the simulation shows plots for the E, M and Cv. Runs multiple loops and writes the Critical Temperatures in a txt file.

Then, `PHSX815_Proj4_read.py` will read Tcs from the txt file,  perform gaussian fit, calculate the p-value for the test and plot it.

## Requirements:
- numpy
- scipy
- matplotlib
- rich (pip install rich)
- numba
