# energy_penetration_sim

__Reading Data Files__

All of the histogram and data files are scaled to integral 1. The x-axis of the histograms and values in data files are in millimeters, and the energies/particles are as described in the file names.  

Each data file is a csv file with delimeter "," and stores the data drawn in the corresponding histogram. Each row of the csv corresponds to one bin of the histogram and has 3 values:

bin_low_edge,bin_high_edge,scaled_bin_value