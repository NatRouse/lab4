### EECS 498: Lab 4
##### Natasha Rouse
##### Due 10/17/2019

*Introduction*

This lab consisted of a (basic) construction of the Navvis mobile sensing system. The Unviersal Robot Description Format (URDF) and the Xacro system were used to render a version of the robot that is visualized in RViz.

*How to launch the system*

To use the given Robot Configuration, visualize it in RViz and open the Joint State Publisher GUI, use:

	roslaunch lab4_nar50 display.launch

Without the GUI, use:

	roslaunch lab4_nar50 display.launch gui:=false


*Notes*

The meshes for the Hokuyo lasers do not seem to be working. They are included in the "robot.xacro" file in the same way they were given in the lab documentation, but they do not seem to be rendering in RViz.
