# New-Arm-

To start simulating the new arm we must do the following 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------


1) you download the package from the libraries in the smart methods website : 
https://s-m.com.sa/smtc/sdb/library.php



2) go to the old meshes file you have created from the previous tasks and delete all the content 



3) add the downloaded files to the meshe file from before 



4) grab the urdf and link it 


5) Put it in the github 


6) copy it's link prepare your terminal 


7) make the command of gitclone and put the link right next to it 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

do these commands for this task 
Creating a directory called catkin in the source file mkdir -p ~/catkin_ws/src

Name it as catkin work cd ~/catkin_ws/

Installing the arm package by using this command catkin_make

Enter the source folder by this command cd ~/catkin_ws/src

Enter the robotic arm package by using this command git clone (THE LINK IN THIS TASK WILL BE DIFFERENT READ THE STEPS BELOW 

Go to the catkin_ws folder cd ~/catkin_ws

All the commands below are the commands needed from ROS rosdep install --from-paths src --ignore-src -r -y

sudo apt-get install ros-melodic-moveit

sudo apt-get install ros-melodic-joint-state-publisher ros-kinetic-joint-state-publisher-gui

sudo apt-get install ros-melodicc-gazebo-ros-control joint-state-publisher

sudo apt-get install ros-melodic-ros-controllers ros-kinetic-ros-control

Enter the bashrc file and enter the following text below sudo nano ~/.bashrc
at the end of the (bashrc) file add the follwing line (source /home/reemaalmurayshid/catkin_ws/devel/setup.bash) then ctrl + o

Update the sources of bashrc using this command source ~/.bashrc

Launch the RVIZ using this command roslaunch robot_arm_pkg check_motors.launch
