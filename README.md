# [ROS仿真] RVIZ加载URDF模型并控制关节运动

## 项目介绍

使用RVIZ仿真软件加载一个配置好的URDF模型，并使用GUI控制机械臂的关节进行运动



## 运行环境

- 操作系统：ubuntu16.04
- ROS版本：kinetic



## 二、详细步骤

- 创建工作目录

```
mkdir ~/work/test/catkin_test_aubo/src
cd ~/work/test/catkin_test_aubo/src
```

- 将代码放到工作目录：~/work/test/catkin_test_aubo/src路径下

l

- 编译

```
cd ~/work/test/catkin_test_aubo/
catkin_make
```

- 运行

```
cd ~/work/test/catkin_test_aubo/src/aubo_description/launch
roslaunch ./display.launch
```

- 效果
  ![rviz_load_urdf](.\img\rviz_load_urdf.png)




