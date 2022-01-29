In this project you will create a 2D occupancy grid and 3D octomap from a simulated environment using your own robot with the RTAB-Map package

- To start creating 2D and 3D map by using RTAB-Map package
```bash
roslaunch my_robot world.launch
roslaunch my_robot rtab.launch 
roslaunch my_robot teleop.launch
```
When your map is ready, you can close rtab.launch terminal


- To load previously created map and start navigation
```bash
roslaunch my_robot world.launch 
roslaunch my_robot rtab.launch localization:=true database_path:=<database_directory>
```

- To view RTAB-Map data
```bash
rtabmap-databaseViewer <database_directory>
```