This project was my final project for the Robotics I course at Rensselaer Polytechnic Institute. For this project my team utilized computer vision to have a camera translate printed out morse code
into alpha-numeric characters. The result was then fed into a loop utilizing a dictionary to control a robotic arm to type out the translated message on a keyboard. For this project I primarily worked 
on the inverse kinematic calculations of the system. I manually measured the distance of each key on the keyboard to the origin point of the robot arm, and perform the inverse kinematic calculations and path generation
to plot the best path for the arm. To ensure that the arm would lower itself directly onto each key, each path included a point directly above the key, had the arm lower itself to press the key, and raised itself back up.
This ensured that the arm would be far enough above the keyboard when moving to the next letter so that it would not crash into the keyboard. A video demonstration of the final project can be viewed through the below link.



https://www.youtube.com/watch?v=kbicyQ2qN0I&ab_channel=JaysonMintz
