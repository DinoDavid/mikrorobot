# mikrorobot

Installer ros jade

http://wiki.ros.org/jade/Installation/Ubuntu

Installer pakker vi bruker:

sudo apt-get install ros-jade-usb-cam
sudo apt-get install ros-jade-rosserial

Sett opp et directory for ROS:

# cd ~
# mkdir catkin_ws
# cd catkin_ws

# catkin_init_workspace

Clone mikrorobot:

# cd ~/catkin_ws/src
# git clone https://github.com/bjornite/mikrorobot
# cd ~/catkin_ws

# catkin_make

# rospack profile
    Sjekk at utskriften inneholder ~/catkin_ws/src
# rosrun mikrobo<tab>
    Dette bør autocomplete til mikrorobot

Last ned ROS Node Automator:

# cd ~
# mkdir RNA
# cd RNA
# git clone https://github.com/ymli81/RosNodeAutomator
