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
* `msg` : ROS messages files for the whole Robotec ecosystem

### Files
* `Battery.msg` : message type which contains data about batteries
* `FiducialArray.msg` :  
* `FiducialMapEntryArray.msg` : 
* `FiducialMapEntry.msg` : 
* `Fiducial.msg` : 
* `Imu.msg` : data from IMU (inertial measurement unit) for navigation
* `PID.msg` : PID (proportional–integral–derivative controller) configration message
* `Velocities.msg` : full velocity data in vector representation