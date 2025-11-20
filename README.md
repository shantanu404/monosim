# MonoSIM

A testbed for control algorithm testbed for monocular vision based ackermann vehicle

### How to run

```bash
$ source /opt/ros/jazzy/setup.bash # Or use ros2 `humble`
$ cd ~/ros2_ws/src
$ git clone https://github.com/shantanu404/monosim.git
$ pip3 install requirments.txt # You can use `virtualenv` too
$ cd ~/ros2_ws
$ colcon build # do not use symlink-install if you are using `virtualenv`
$ source install/local_setup.bash
$ ros2 launch monosim mpc.launch.py
```
