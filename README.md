# AR follow the leader
This repository is a ROS package that contains follow the leader demo showing the capabilities of  the Robotont platform to detect and follow the AR Tag.

## Prerequisites installed on the Robotont on-board computer
 * [ar_track_alvar](http://wiki.ros.org/ar_track_alvar)

## Launching the demo
**On Robotont on-board computer**, launch ar_follow_the_leader.launch (change 5 with the AR tag number you intend to follow)<br/>
```bash
roslaunch ar_follow_the_leader ar_follow_the_leader.launch marker_id:=5
```

**On PC**, launch ar_marker_display.launch to visualize the result<br/>
```bash
roslaunch ar_follow_the_leader ar_marker_display.launch
```