## Robot Package Template

This is a GitHub template. You can make your own copy by clicking the green "Use this template" button.

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `my_bot` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has direcctories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).

## How to initialise

1) create directory: ~/dev_ws/src
2) clone this repository under the directory as mentioned
3) cd to dev_ws
4) build by entering: colcon build --symlink-install

## Other useful commands

setup bash with: source install/setup.bash
launch ROS with: ros2 launch robocock rsp.launch.py
run rviz with: ros2 run rviz2 rviz2
run empty joint state publisher with: ros2 run joint_state_publisher_gui joint_state_publisher_gui