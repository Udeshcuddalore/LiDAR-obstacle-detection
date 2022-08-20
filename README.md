# Lidar Object bstacle-detection
The goal of the project is to consistantly detect obstacles in a real LiDAR point cloud stream. This is achieved by filtering, segmenting and clustering the point cloud. LiDAR is an active sensor that provided real-time spatial perception of the environment.

![](https://raw.githubusercontent.com/udacity/SFND_Lidar_Obstacle_Detection/master/media/ObstacleDetectionFPS.gif)

## Lidar
Lidar is an active sensor that emits laser beams and receives them upon reflection. The distance of the obstructing surface is computed using the Time of Flight and speed of the corresponding beam. Each such beam, upon 360 degrees rotation of the Lidar scanner, provides the distances of the obstacles present in the contemporary environment. In addition, the intensities of the reflected beams are recorded. This process is called environment perception, which is the first step in the motion planning of an autonomous robot.

The point cloud used in this project is obtained using a Velodyne VLP-64 Lidar, where 64 stands for the number of laser emitters in the emitter array. One scan of this sensor generates 256,000 points.

## Workspace
The workspace provided in the Sensor Fusion Engineer Nanodegree Program (SFND) classroom comes preinstallated with everything that you need to finish the exercises and projects. Versions used by Udacity for this ND are as follows:

Ubuntu 16.04
PCL - v1.7.2
C++ v11
gcc v5.5
Note The [CMakeLists.txt] file provided in this repo can be used locally if you have the same package versions as mentioned above. If you want to run this project locally (outside the Udacity workspace), please follow the steps under the Local Installation section.
## Point Cloud Data 

