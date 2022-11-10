## WYXMJL-Line_Following_and_Parking_via_ArucoMarker
This is the lab4 resource for EE346.

We aim to achieve lane following and parking via the detection of aruco marker.

This work was done with the help of Prof.Zhang and all TAs.

Team numbers: WYX, MJL.

# Steps:


## 1. Clone the source codes.
  cd ~/catkin_ws/src
  
  git clone git@github.com:MJLNSN/WYXMJL-Line_Following_and_Parking_via_ArucoMarker.git
  
## 2. Connect the turtlebot to pc.
  ssh pi@192.168.3.29
  
  raspberrypi (password) 
  
## 3. Catkin make the package
  cd ..
  
  catkin_make

## 4. Active all the nodes
  cd ..
  
  catkin_make
   
## 5. Run the codes by using launch file
   source ~/catkin_ws/devel/setup.bash
   
   roslaunch lane_following race_track.launch 


 ![image](https://github.com/MJLNSN/WYXMJL-Line_Following_and_Parking_via_ArucoMarker/blob/main/data/demo.gif)
