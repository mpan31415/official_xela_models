# xela allegrohand urdf

## 1. Launch xela allegrohand model view
### 1.1 Build 
```
cd ~/work_space
colcon build
```
### 1.2 urdfs
#### - Left hand:
```
urdf/allegro_hand_left_curved.xacro
```
#### - Right hand:
```
urdf/allegro_hand_right_curved.xacro
```
### 1.3 Launch for left hand view
#### Term 1:
```
source install/setup.bash
ros2 launch xela_models xacro_launch.py xela_sensor:=allegro_hand_left_curved
```
### 1.4 Launch for right hand view
#### Term 1:
```
source install/setup.bash
ros2 launch xela_models xacro_launch.py xela_sensor:=allegro_hand_right_curved
```
