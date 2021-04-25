# lidar_based_perception

ROS package for perception based on lidar

## 安装
 - 建立工作空间并拷贝这个库
   ```Shell
   mkdir -p ros_ws/src
   cd ros_ws/src
   git clone https://github.com/shangjie-li/lidar_based_perception.git --recursive
   git clone https://github.com/shangjie-li/perception_msgs.git
   cd ..
   catkin_make
   ```

## 运行
 - 启动`lidar_based_perception`
   ```Shell
   roslaunch lbp lidar_based_perception.launch
   ```
   
