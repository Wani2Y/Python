# Python script for Maya

## project "SIMM modelling"
This project is part of the Chapter 8 of my PhD thesis. Link to the thesis will be updated once it becomes publicly available.

## Description
This script compute two elements for SIMM models:
1) the difference as measured by the linear MMatrix between a world oriented joint and an anatomically sounded joint.
The last column and row of the MMatrix are removed as SIMM does not require those information.
2) the linear spatial difference between two objects

I used this script to compute the axial orientation of each anatomical joints and the spatial position of each bone used in SIMM models.

Modify the write mode on line 72 as needed. Be ware of the order of selection in Maya before running the script.

## License
This repository is licensed under the MIT License.