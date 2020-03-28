# aruco_mavconn
aruco_mavconn is the porting to (non-ROS) C/C++ of the positioning system based on Aruco Boards described in this Ardupilot wiki page (https://ardupilot.org/dev/docs/ros-aruco-detection.html).

Mavlink communications are managed through MAVCONN library (libmavconn - https://github.com/mavlink/mavros/tree/master/libmavconn)

The intent was that of learning how to use libmavconn and a little bit more of OpenCV while at the same time obtaining a lighter application to run on Single Board Computer.

More info on this blog post:
https://discuss.ardupilot.org/t/using-mavconn-library-for-sending-non-gps-navigation-messages-in-c-c/54105
