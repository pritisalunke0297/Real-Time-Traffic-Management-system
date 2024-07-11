# Real-Time-Traffic-Management-system
This Adaptive Traffic Signal Timer uses live images from the cameras at traffic junctions for traffic density calculation using YOLO object detection and sets the signal timers accordingly, thus reducing the traffic congestion on roads, providing faster transit to people, and reducing fuel consumption.
Implementation Details
This project can be broken down into 3 modules:

Vehicle Detection Module - This module is responsible for detecting the number of vehicles in the image received as input from the camera. More specifically, it will provide as output the number of vehicles of each vehicle class such as car, bike, bus, truck, and rickshaw.

Signal Switching Algorithm - This algorithm updates the red, green, and yellow times of all signals. These timers are set bases on the count of vehicles of each class received from the vehicle detection module and several other factors such as the number of lanes, average speed of each class of vehicle, etc.

Simulation Module - A simulation is developed from scratch using Pygame library to simulate traffic signals and vehicles moving across a traffic intersection.
