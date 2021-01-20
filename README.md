ROS 연습
이 폴더를 메인 PC에 git clone한 후, 이폴더의 src 폴더와 docker의 ROS src 폴더를 연동시킴.


sudo docker run --gpus all -it --privileged     -v /tmp/.X11-unix:/tmp/.X11-unix:ro -/home/jw/jinwoo_ws/ROS_Project_JW/src:/root/catkin_ws/src      -e DISPLAY=:0     -p 14556:14556/udp
