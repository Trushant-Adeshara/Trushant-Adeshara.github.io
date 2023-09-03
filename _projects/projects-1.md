---
title: "eYantra Robotics Competition"
excerpt: "Developed pre-emptive scheduling algorithm for survey and rescue. <br/><img src='/images/projects/eyrc/eyrc_pv.jpg'>"
collection: projects
---

<p style="text-align: justify">
e-Yantra Robotics Competition is a 6 month long competition wherein you are allocated a theme and there are tasks which need to be accomplished in a team of 4. The themes are based on real world problems and we were assigned Survey and Rescue theme in which we have to develop a pre-emptive scheduling algorithm for a drone which will aid individuals afflicted by natural disaster.</p>

<p style="text-align: justify">
Task 0 was setting up the system and the simulator we used was Gazebo. Other software we used was ROS (Robot Operating System) Kinetic and underlying operating system was Ubuntu 16.04. Primary language of implementation was python. Once that is done, we recevied Task 1 which was as follow:</p>

<p style="text-align: justify">
Task 1.1 - Position hold of the drone in a simulation
	   The drone should hold its position in the given simulation scene at the given point [2, 2, 20] using the PID control algorithm.
</p>

<p style="text-align: justify">
<iframe width="420" height="315" src="https://youtube.com/watch?v=xRDrj8BBL4Y&feature=shared" frameborder="0" allowfullscreen></iframe></p>

<p style="text-align: justify">
Task 1.2 - Waypoint navigation of the drone in a simulation
	   The drone should visit the given waypoint coordinates in the simulation using the PID control algorithm. Waypoings are in the form (x, y, z).
	   [(0.2, 0, 23), (3.5, -3.3, 23), (-4.4, -4.6, 20.7), (-6.0, 6.3, 18.3), (5.0, 5.3, 16.3)]
</p>

<p style="text-align: justify">
<iframe width="420" height="315" src="https://youtu.be/p4Qnun8-WfE" frameborder="0" allowfullscreen></iframe></p>

<p style="text-align: justify">
Once the simluation was complete, we were given physical hardware to implement. Alongwith that we were provided with an overhead camera, RGB beacon LED and we used WayCon Marker to locate drone through the camera after its calibration.</p>

<p style="text-align: justify">
In the final task a random sequence was given for three colors, each indicating a specific service with a priority level. There were three colors:
Red - Rescue
Green - Food
Blue - Medicine
</p>

<p style="text-align: justify">
Highest priority was given to Rescue (Red) but to accomplish that the drone has to visit homing position after the service. Second priority was given to Medicine (Blue) and last one to Food (Green). I alongside my team developed first tuned the PID algorithm for the physical drone and later on developed a pre-emptive schedluing algorithm. Overall it was a rewarding experience filled with sleepless nights and managing exams with task submission deadlines. One hardship I faced was that the team constituted of four individuals but half way through we were just two remaining. This was my first thorough experience working with ROS. I am grateful to eYantra for providing me this opportunity and especially to Prof. Kavi Arya, the man behind this initiative.</p>

<p style="text-align: justify">
<iframe width="420" height="315" src="https://youtu.be/91-KuGHN9CY" frameboarder="0" allowfullscreen></iframe></p>
