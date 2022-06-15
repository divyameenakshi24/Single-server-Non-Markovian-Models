# Single-server-Non-Markovian-Model

# Aim : 
To find 
      (a) average  number of materials in the conveyor
      (b) suitable length of conveyor
      (c) waitinging time of the material in the conveyor,
if arrival rate of material  follows poisson process 5 per minuates and serivice rate of lathe machine follows 
constant service rate 6 per minutes.


# Software required :  

Visual components and Python

# Theory:

  Queueing models in which the arrivalas and departures do not follow the Poisson distribution are complex.
  But, we can find the average number of customers in the sysem for a particular non-Markovian model (M/G/1):(inf/GD model)
 (M indicates the number of arrivals in time t follows Poisson process) using Pollazack-Khinechine formula
 
  ![image](https://user-images.githubusercontent.com/104613195/173732900-b60f7a92-f18b-4faa-910d-0835cccaa44b.png)

 
# Procedure :
 
1. Calcualte average number of materials to be waitted in the conveyor using given data.
2. Create a empty project  in visual component tool and add visual legacy component to the project.
3. Drag a feeder and place in a place and choose the appropriate materal.
4. Calculate conveyor length usng material size and average number of materials to be waitted in the conveyor
5. Choose the two conveors from components,  add one conveyor with feeder.
6. Drag Lathe machne from machine library and place in the appropirate place.
7. Drag machine trending inlet and outlet from visual legacy and add them to the two conyeors in the approprate manner.
8. Drag robot manager and robot from visual legacy and place in between two conveyors.
9. Connect all machine trending  inlet, outlet, robot manager and lathe machine using interface menu.
10. Run the program.

# Program :

 

# Results and Output : 
 


