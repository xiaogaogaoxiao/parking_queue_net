# sciadvances2018
Neccessariy code and data to reproduce results contain in "Fusing multiple data streams to control urban congestion caused by drivers searching for curbside parking" by Chase Dowling, Tanner Fiez, Lillian Ratliff, and Baosen Zhang, submitted to Science Advances in December, 2017.

This repository contains two main directories:
    -./congestion: code and data neccessary to reproduce congestion and time delay estimation results
    -./spatial-data-analysis: a git submodule (owned by Tanner Fiez, <https://github.com/fiezt/spatial-data-analysis>) containing code and data neccessary to reproduce GMM model results
    
Instructions for re-executing code can be found in each respective directory. 

Note ./congestion/data contains all essential data for both experiment directories, as well as a data manifest (data_notes.txt) with detailed descriptions of the contents of each data file and subdirectory.

## basic dependencies

All code was written and tested in unix environments. 

-Python 2.7+

pandas==0.20.3

seaborn==0.8.1

scipy==0.19.1

gmplot==1.1.1

matplotlib==2.0.2

numpy==1.13.1

scikit_learn==0.19.0


## support

Questions can be sent directly to <cdowling@uw.edu>
