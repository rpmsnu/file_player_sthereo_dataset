# File player for stereo thermal dataset

Maintainer: Seungsang Yun (seungsang@snu.ac.kr)

## 1. Obtain dependent package (defined msg)

```
$mkdir ~/catkin_ws
$cd ~/catkin_ws
$mkdir src
$cd src
$git clone https://github.com/rpmsnu/file_player_sthereo_dataset.git
$cd ~/catkin_ws/src/file_player_sthereo_dataset
$bash install_depend_package.sh
```

## 2. Build workspace

```
$cd ~/catkin_ws
$catkin_make
```

## 3. Run file player

```
$source devel/setup.bash
$roslaunch file_player file_player.launch
```

## 4. Load data files and play

1. Click 'Load' button.
2. Choose data set folder including sensor_data folder and calibration folder.
3. The player button starts publishing data in the ROS message.
4. The Stop skip button skips data while the vehicle is stationary for convenience.
5. The loop button resumes when playback is finished.

## 5. Contributor
* Jinyong Jeong : The original author
