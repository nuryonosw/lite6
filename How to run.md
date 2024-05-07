
```bash 
roslaunch uf_robot_moveit_config lite6_moveit_realmove.launch robot_ip:=192.168.1.178
```

```bash
roslaunch xarm_planner robot_planner_realmove.launch robot_ip:=192.168.1.178 robot_type:=lite dof:=6
```
```bash
roslaunch uf_robot_moveit_config lite6_moveit_gazebo.launch add_gripper:=true add_realsense_d435i:=true
```
