# Autonomous-Maze-Solver-Bot-using-Nucleo-board
  The project's central objective is to design and develop an autonomous robot capable of 
navigating through the complexities of a maze. Military operations often involve navigating 
through complex and hazardous environments where the presence of obstacles, such as 
debris, barriers, and uneven terrain, can pose significant challenges. An autonomous 
maze-solving robot equipped with the STM32F446RE microcontroller provides a solution by 
autonomously navigating these environments, avoiding obstacles, and gathering crucial 
intelligence. Such a robot can be deployed in urban warfare for building clearance, disaster 
response to locate survivors, and explosive ordnance disposal to identify and map explosive 
devices.
  When placed at the start position, the robot begins moving along the path until it encounters an  
obstacle. This is detected by the ultrasonic sensor, causing the robot to stop and turn right. If  
there’s another obstacle to the right, the robot stops and turns 180 degrees, reverting to its   
original position. If the path is clear, the robot advances. However, if an obstacle is also present  
to the left, the robot moves backward. This algorithm continues until the robot reaches the 
endpoint. 
