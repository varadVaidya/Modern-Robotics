# Modern Robotics
This repository is to show some of the work done I did in the Coursera specialization Modern Robotics.

No code is added to the Git to honour the Cousera Code of Honour of not sharing the assignment code, especially as these assignments are Peer Graded.

## Course 2 : Robot Kinematics
This assignment involved to use the Inverse Kinematics alogrithm to find out the joint position required to achieve a desired configration and then animate it using V-Rep.
![Course2.gif](Course2.gif?raw=True "Course2.gif")

## Course 3 : Robot Dynamics
This assignment used the concept of Dynamics of Open Chains to simulate a robot arm freely falling in graviy. And intersting case occurs in the second simulation beacuse the initial joint angles are such that the robot acts like a double pendulum and follows a chaotic dynamics. The forward and inverse dynamics are implemented in Python and simulated in V-Rep.

* Simulation 1
    * Free Fall in Gravity.
    ![Sim1.gif](Sim1.gif?raw=True "Sim1.gif")
* Simulation 2
    * Chaotic System due to singularity.
    ![Sim2.gif](Sim2.gif?raw=True "Sim2.gif")
## Course 4 : Robot Motion Planning and Control
In this assignment a Probabilistic Road Map was developed to map the given space. The algorithm generated random points in the plane as nodes and created edges based on their feasibility in the map, i.e. if the node was in the obstace region the node was removed from further calculations\
Similarly if two edges intersected any of the obstacles then that edge connecting those particular nodes were not used for the planning problem.

After the nodes and edges are formed then an A* algorithm to find the optimal path between the start node and the end node.\
One important point in the implementation is that the the solution reaches optimal as the number of nodes tends to infinity.\
### Solutions
The solutions obtained from the algorithm are shown below. N is the total number of the nodes.

* Solution at N = 50
    \
    ![N50 solution](N50.png?raw=True "N50 solution")
* Solution at N = 100
    \
    ![N100 solution](N100.png?raw=True "N100 solution")
* Solution at N = 200
    \
    ![N200 solution](N200.png?raw=True "N200 solution")

