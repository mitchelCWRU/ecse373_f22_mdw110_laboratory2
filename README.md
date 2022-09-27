Setup:
======
First run:
`source devel/setup.bash`
from the top-level directory

Launch:
========

To run with the joint_state_publisher GUI:
------------------------------------------
`roslaunch navvis_description display.launch use_xacro:=true`

To run without the joint_state_publisher GUI:
---------------------------------------------
`roslaunch navvis_description display.launch use_xacro:=true use_joint_state_publisher_gui:=false`

