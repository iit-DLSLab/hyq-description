# hyq-description
This package contains the description (mechanical, kinematic, visual, etc.) of the different HyQ robots. The files in this package are parsed and used by a variety of other components. Most users will not interact directly with this package.

Issue so far:

rviz.launch
No such file or directory: /home/steven/terrain_ws/src/hyq-description/robots/hyq_model_ordered.urdf.xacro [Errno 2] No such file or directory: '/home/steven/terrain_ws/src/hyq-description/robots/hyq_model_ordered.urdf.xacro'
RLException: while processing /home/steven/terrain_ws/src/hyq-description/launch/upload.launch:
Invalid <param> tag: Cannot load command parameter [hyq/robot_model]: command [['/opt/ros/noetic/lib/xacro/xacro', '--inorder', '/home/steven/terrain_ws/src/hyq-description/robots/hyq_model_ordered.urdf.xacro']] returned with code [2].

world.launch
need to install ros_impedance_controller
