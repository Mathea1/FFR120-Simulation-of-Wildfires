# Simulation of Wildfires
Partaking individuals in the project include: Alfons Otterspeer 

# Introduction and approach
The study investigates the relationship between forest size and the eventual wildfire damage with additional parameters being present. With the worlds ongoing pollution crisis the average temperature is steadily increasing resulting in a growing number of forest fires around the world. By simulating the scenarios with various surroundings and to try different strategies to stop/prevent wildfires may hopefully be found.

# Abstract
This study aims to investigate how a randomly generated forest depends on the aspects of wind speed and terrain generation. The two dimensional wind speed effects the direction and the extent of the fire spread. Generating the terrain is based upon a transformed ising model algorithm to make it continous. Values below a certain thershold may be put to being unignateble to simulate wet terrain. With a continous noise map we can calculate the gradient and determine if the fire can spread from one tree to another.  

# Methodology
Firstly a terrain is generated using the ising model. To make it continous we add the neighbour values and divide by the number of neighbours for x iterations, this might still be to "edgy". Therefore we scale it. The values then determine the type of terrain. Gradients are calculated and evaluated. Then the forest and wind speed is initiated and iterated forward in time. 

# Repository overview and usage


# Refereneces
author = {Argun, Aykut and Callegari, Agnese and Volpe, Giovanni},
title = {Forest fires},
booktitle = {Simulation of Complex Systems},
publisher = {IOP Publishing},
year = {2021},
series = {2053-2563},
type = {Book Chapter},
pages = {3-1 to 3-11},
abstract = {Modeling the growth of a forest that experiences the repeated occurrence of fires provides a natural tool with which to introduce concepts related to power-law distributions and self-organized criticality, which can be used to understand a broad range of phenomena.},
url = {https://doi.org/10.1088/978-0-7503-3843-1ch3},
doi = {10.1088/978-0-7503-3843-1ch3},
isbn = {978-0-7503-3843-1}





        
