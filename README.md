# lidar_based_perception

ROS package for perception based on lidar

## 安装
 - 建立工作空间并拷贝这个库
   ```Shell
   mkdir -p ros_ws/src
   cd ros_ws/src
   git clone https://github.com/shangjie-li/lidar_based_perception.git --recursive
   cd ..
   catkin_make
   ```

## 运行
 - 启动`lidar_based_perception`
   ```Shell
   cd lidar_based_perception
   roslaunch multiple_target_tracking lidar_based_perception.launch
   ```
   
