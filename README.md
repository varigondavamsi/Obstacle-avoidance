# Obstacle-avoidance
The idea of this project is to detect the obstacles using multiple ultra sonic sensors, sending these values  to pixhawk flight controller.
Objective: construction of cheap obstacle avoidance system for drone using microcontroller and ultrasonic sensors by modulating receiver signals
(non conventional method of using mavlink commands connection to flight controller )
# Stages of the project –
1. To make a code to detect obstacles using ultrasonic sensors in four directions at once.
2. To write a code to read the receiver values. (repo: https://github.com/varigondavamsi/Arduino-PWM-receiver)
3. Write a code to generate pwm values.
4. To measure the change in motion of the drone with change in receiver values.
5. Combine all these to make a obstacle avoidance drone with proper time stamping analysis of input and output signals.
# Current Status
The 1st three stages were easy to do.
But, the project has to be stopped due to following reasons
1. There is a considerable delay in change of the pwm signal after the obstacle detection.  
2. Analysing the pwm signals and changing the values as per the obstacles is not a good option as this processing delay causes considerable changes in the drone motion.
  

