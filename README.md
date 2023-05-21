
# This a lab for Design and Principles of robotics 
___________________________________________________

First -> Download VB and install ubonto V 20.04.6 , then install ROS by following the instruction on their website.

--------------------

Open the terminal (CTRL+ALT+T)
roscore
![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/fe9afff6-d7be-4e98-9587-6c645410f6af)


#Part I
Turtlesim Node
We will start the turtlesim node and explore its properties. Execute roscore and in a new terminal create the turtlesim node from the package turtlesim:

•	$ rosrun turtlesim turtlesim_node

![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/9ccccb73-9f5d-43f6-a1a1-24f4cf52f29e)
![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/1d3e316c-6ef7-4921-8286-f353722e7c92)

• $ rosnode list

![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/1c6907fa-420d-4fae-9f91-955836448ba4)


• $ rosnode info /turtlesim

![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/d8d61b1d-6d45-45c7-a474-05bf46f447da)

• $ rosrun turtlesim turtle_teleop_key

![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/a5afa656-b5bf-4cfb-a95e-d2697bf2939b)
![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/25ec261a-459b-440a-a133-55dc4eaa7e08)

![Move turtel](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/4842c223-ea60-4ba3-bb60-7323ec5571a1)


• $ rosnode list
![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/03a6aea0-5a1d-4f46-97d1-9ff550017cc7)

display the graph of nodes and topics using rosrun rqt_graph rqt_graph

![image](https://github.com/Walaa-AI/Ros-Turtle/assets/107875617/7a562a5f-03c0-4324-a953-920b337d946d)




