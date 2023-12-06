# PSU-Robotics-2024-Maze-Solver-
This repository includes CAD and the necessary code to build a maze solving robot using basic Arduino hardware. It received 1st place at the Fall 2024 PSU Robotics Challenge 

This robot competed under the name "I Don't Care". It's design can be accredited to Jeremiah Ondrasik, Teagan Sharp (tjs6866@psu.edu), and Sydney Graver (sjg6347@psu.edu).

The CAD includes 7 SolidWorks part files and 1 assembly. To have the assembly file work correctly the files will need to properly selected when opening the file. If there are any issues feel free to contact Jeremiah as he did the CAD design.

The code file names Challenge_Final was used on the final robot when it went to competition. The New Ping arduino library needs to be downloaded for the program to work properly. There are still a few issues with the line fowling as we ran into a major constraint with the arduino's processing power. We originally had a very well defined line fowling code which only used the IR sensors however once we implemented the depth first searching algorithm (with the Ultrasonic sensors) we ran into processing issues of which we didn't have time to resolve. This caused us to simplify the code a lot, which makes it not as smooth, however it still completed the intended goal of solving the mazes within the time constant, and doing it faster than all of the other teams. If there are any questions with the code Jeremiah wrote the majority of it and Teagan / Sydney solved some of the remaining issues. 

If there are any questions about the composition Teagan should be contacted as he entered the robot into the composition.