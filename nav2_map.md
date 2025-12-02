ros2 launch nav2_bringup bringup_launch.py \
use_sim_time:=False \
map:=/home/user/map/my_map.yaml \
params_file:=/home/user/params/nav2_params.yaml

ros2 launch nav2_bringup bringup_launch.py \
use_sim_time:=False \
map:=/home/robot/ros2_ws/src/tetra/tetra_maps/road.yaml \
params_file:=/opt/ros/humble/share/nav2_bringup/params/nav2_params.yaml
