**EEE3088F DESIGN PROJECT**  
The project requires the construction of two submodules that interface with a micromouse robot. The robot is designed to complete a maze after finding the most optimal path to traverse.
The two submodules are for the **power** and **sensing** requirements of the micromouse. All design schematics and datasheets considered can be found in this repository.  

**POWER**  
The power submodule is required to distrubute the power from a 1S1P battery to the motors on the micromouse as well as power the other submodules such as the processor and the sensing apparatus. 
THe system is also required to monitor the battery's state of charge (SoC) through the processor's ADC.


  
**SENSING**  
The sensing subsystem is required to, at close range(+-5cm) produce a voltage to the micro controller. This voltage must be distinguishable from a further range output(+10cm). It is also required to not drain the battery of the micro mouse as it needs to traverse a maze for roughly 10 minutes.
