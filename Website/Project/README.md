# Specifications
The machine is expected to deploy a number of small size traffic cones within a designed lane. The lane is 25 cm wide and 400 cm long, and it is defined by two lines along the length made of black hockey tape with a width of 2 cm. The deployment of the cones during the operation depends on whether the machine detects a "hole" or "crack" on the ground as well as their distance from each other. Each hole is represented by a square mark on the floor, made of black hockey tape and with a length of 4 cm, whose center is on the lane centerline. Each crack is represented by a lateral line normal to the lane borderlines with a length of 15 cm and width of 2 cm. 

# Operation
The machine is initially positioned behind the Start Line in standby mode. The operation begins by pressing the <*start*> button on the keypad. The robot then travels along the lane until it detects a hole or crack. If the machine detects a hole, the robot deploys one cone on top of the hole, such that the cone completely covers the hole. If the robot detects a crack, the robot deploys two cones on top of the crack, such that they do not contact each other and each covers a least 5 cm of the crack. 

# Constraints
* The entire prototype shall completely fit within a 50x50x50 cm<sup>3</sup> envelope at all operation times.
* The weight of the machine (without the cones) shall not exceed 8 kg.
* The total prototype costs shall not exceed $230 CAD.
* The machine must have an easily-accessible emergency STOP switch that stops all the mechanical moving parts immediately. 
* The machine must use its own on-board power supply during the operation.
* The machine must be fully autonomous, and no interaction with an external PC or remote control is permitted during the operation. 
