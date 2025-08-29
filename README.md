亚博X3自用雷达SLAM

操作详见 https://www.yuque.com/u57108390/hpeee6

cartographer部分是在backpack_2d.launch的基础上修改的

navigation的部分是自制的，加入亚博官方的参数

启动方法：

roslaunch yahboomcar_nav laser_bringup.launch   

roslaunch cartographer_ros backpack_2d.launch

movebase启动在cartographer这个backpack_2d里了


cartographer用yahboom_map.launch就好，加入这个movebaselink即可SLAM



此项目cartographer只发布map到odom，yahboom文件在此之上还发布了odom到Baselink





