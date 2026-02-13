# tiny_arm_description

ROS2 description package for the tiny_arm robot! (URDF/Xacro + meshes + RViz + launch).

## Build
```bash
mkdir -p ~/arm_ws/src
cd ~/arm_ws/src
git clone <REPO_URL>
cd ..
colcon build --symlink-install
source install/setup.bash
