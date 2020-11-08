# ROS messages for Robotec projects
The package contains custom ROS messages for Robotec projects.

## Project structure
```
.
├── msg
│   ├── Battery.msg
│   ├── FiducialArray.msg
│   ├── FiducialMapEntryArray.msg
│   ├── FiducialMapEntry.msg
│   ├── Fiducial.msg
│   ├── Imu.msg
│   ├── PID.msg
│   └── Velocities.msg
├── CMakeLists.txt
├── package.xml
└── README.md
```

### Folders
* `msg`

    ROS messages files for the whole Robotec ecosystem

### Files
* `Battery.msg`

    Message type which contains data about batteries

* `FiducialArray.msg`

    Array of points for robot to achieve (full path)

* `FiducialMapEntryArray.msg`

    Point on a map for robot to achieve

* `FiducialMapEntry.msg`

    Array of points on a map for robot to achieve

* `Fiducial.msg`

    Points for robot to achieve (planned path)

* `Imu.msg`

    Data from IMU (inertial measurement unit) for navigation

* `PID.msg`

    PID (proportional–integral–derivative controller) configration message

* `Velocities.msg`

    Full velocity data in vector representation