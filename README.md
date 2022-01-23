In this project you will create a 2D occupancy grid and 3D octomap from a simulated environment using your own robot with the RTAB-Map package

- To start creating 2D and 3D map by using RTAB-Map package
```bash
roslaunch my_robot world.launch
roslaunch my_robot mapping.launch 
roslaunch my_robot teleop.launch
```
When your map is ready, you can close mapping.launch terminal


- To start load previously created map
```bash
roslaunch my_robot world.launch 
roslaunch my_robot localization.launch 
```

- To view RTAB-Map data
```bash
rtabmap-databaseViewer <database_directory>
```