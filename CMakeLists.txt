cmake_minimum_required(VERSION 2.8.3)
project(toypkg)

find_package(catkin REQUIRED)

catkin_python_setup()

###################################
## catkin specific configuration ##
###################################

catkin_package()

#############
## Install ##
#############

#############
## Testing ##
#############

## Add folders to be run by python nosetests
catkin_add_nosetests(test)
