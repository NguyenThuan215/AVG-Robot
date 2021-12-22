# AVG-Robot
ROS package for the avg robot 


#Subscriber
rosrun avg_robot keyboard_robot_subscriber
rosrun avg_robot motor_control_subscriber
rosrun avg_robot distance_warning_subscriber
rosrun avg_robot distance_motor_status_subscriber

#Server 
rosrun avg_robot ir_server
rosrun avg_robot map_navigation_server

#Publisher
rosrun avg_robot keyboard_robot_publisher
rosrun avg_robot distance_publisher 10

#Client
rosrun avg_robot ir_client 0 1 1 1 0
rosrun avg_robot map_navigation_client 12 1 17