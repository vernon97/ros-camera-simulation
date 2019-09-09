1.运行launch/cam.launch
2.运行scripts/robot_teleop.py控制小车运动
3.调整小车位置通过：gazebo中直接移动/通过节点移动/通过launch文件设置初始位置
4.urdf中放置模型文件
5.worlds中放置地图文件

6.在运行launch之后在运行命令行：
roslaunch web_video_server web_video.launch
即可在http://127.0.0.1:8080 收到视频流
