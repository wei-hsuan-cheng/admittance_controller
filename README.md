# admittance_controller

## Prerequisites

Install ROS 2 Humble (or a newer distro with the same APIs).

## Build and Run Demo

```bash
# Clone this repository
git clone \
  https://github.com/wei-hsuan-cheng/admittance_controller.git \
  -b humble

# rosdep install
rosdep update
rosdep install --from-paths src --ignore-src -r -y

# Build and install
cd ~/ros2_ws
colcon build --symlink-install \
  --packages-select admittance_controller \
  --parallel-workers 4 --executor sequential \
  && . install/setup.bash
```

## Contact

- **Author**: Wei-Hsuan Cheng [(johnathancheng0125@gmail.com)](mailto:johnathancheng0125@gmail.com)
- **Homepage**: [wei-hsuan-cheng](https://wei-hsuan-cheng.github.io)
- **GitHub**: [wei-hsuan-cheng](https://github.com/wei-hsuan-cheng)