^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package tiago_bringup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.24 (2019-07-08)
-------------------

2.0.23 (2019-06-07)
-------------------

2.0.22 (2019-05-21)
-------------------

2.0.21 (2019-05-13)
-------------------
* Merge branch 'endoscope_cam_fix' into 'erbium-devel'
  changed the frame rate to fix libuvc invalid mode error
  See merge request robots/tiago_robot!84
* changed the frame rate to fix libuvc invalid mode error
* Contributors: Sai Kishor Kothakota, Victor Lopez

2.0.20 (2019-05-09)
-------------------
* Merge branch 'no_wrist_gravity' into 'erbium-devel'
  Add gravity no wrist for new wrist model
  See merge request robots/tiago_robot!81
* Add gravity no wrist for new wrist model
* Contributors: Adria Roig, Victor Lopez

2.0.19 (2019-05-02)
-------------------
* Merge branch 'add_footprint_wsg' into 'erbium-devel'
  Add Dynamic footprint dor WSG config
  See merge request robots/tiago_robot!83
* Add Dynamic footprint dor WSG config
* Contributors: Victor Lopez, davidfernandez

2.0.18 (2019-04-23)
-------------------

2.0.17 (2019-04-12)
-------------------

2.0.16 (2019-04-12)
-------------------

2.0.15 (2019-04-05)
-------------------

2.0.14 (2019-04-03)
-------------------
* Remove gripper usb cam, will be moved package
* Contributors: Victor Lopez

2.0.13 (2019-03-28)
-------------------
* Merge branch 'incrementer' into 'erbium-devel'
  Add new incrementer in the bringup
  See merge request robots/tiago_robot!79
* Add new incrementer in the bringup
* Contributors: Adria Roig, Victor Lopez

2.0.12 (2019-03-26)
-------------------
* Merge branch 'fix-missing-param' into 'erbium-devel'
  Forward correct arguments, and require them for dynamic_footprint
  See merge request robots/tiago_robot!78
* Forward correct arguments, and require them for dynamic_footprint
* Contributors: Victor Lopez

2.0.11 (2019-03-26)
-------------------

2.0.10 (2019-03-26)
-------------------

2.0.9 (2019-03-22)
------------------
* Merge branch 'iron_home_motion' into 'erbium-devel'
  added home motion for TIAGo Iron
  See merge request robots/tiago_robot!77
* Regenerate motion and fix missing endline
* added home motion for TIAGo Iron
* Contributors: Sai Kishor Kothakota, Victor Lopez

2.0.8 (2019-03-15)
------------------
* Merge branch 'teb_planner' into 'erbium-devel'
  Add base and end-effector to dynamic footprint
  See merge request robots/tiago_robot!74
* Add base and end-effector to dynamic footprint
* Merge branch 'minor-fixes' into 'erbium-devel'
  Minor fixes
  See merge request robots/tiago_robot!72
* Fix missing ft data when using wsg gripper without ft sensor
* Contributors: Victor Lopez, davidfernandez

2.0.7 (2019-03-14)
------------------

2.0.6 (2019-03-12)
------------------

2.0.5 (2019-02-26)
------------------

2.0.4 (2019-02-08)
------------------

2.0.3 (2019-02-05)
------------------
* Merge branch 'fix-motion-names' into 'erbium-devel'
  Fix motion names
  See merge request robots/tiago_robot!66
* Fix motion names
* Remove usages of pass_all_args, not supported in kinetic yet
* Contributors: Victor Lopez

2.0.2 (2018-12-21)
------------------
* Fix wrong generation of wsg without ft
* Contributors: Victor Lopez

2.0.1 (2018-12-20)
------------------
* Modify prepare_grasp motion
* Contributors: Victor Lopez

2.0.0 (2018-12-19)
------------------
* Merge branch 'specifics-refactor' into 'erbium-devel'
  Generate automatically play_motion and approach_planner configs
  See merge request robots/tiago_robot!65
* Remove deprecated files
* Remove default parameters to avoid errors
* fixes
* Forward joystick arguments
* More refactor
* Add head and migrate controller launch
* Parametrize urdf
* Split tiago_hardware
* Change joy_teleop handling
* Change dynamic_footprint handling
* Generate automatically play_motion and approach_planner configs
* 1.0.23
* changelog
* Contributors: Procópio Stein, Victor Lopez

1.0.23 (2018-12-05)
-------------------
* Merge branch 'launch_robot_pose' into 'erbium-devel'
  added robot_pose in tiago_bringup.launch
  See merge request robots/tiago_robot!61
* added robot_pose in tiago_bringup.launch
* Contributors: Jordi Pages, Procópio Stein

1.0.22 (2018-12-04)
-------------------

1.0.21 (2018-11-29)
-------------------

1.0.20 (2018-11-19)
-------------------
* Merge branch 'add-grasping-motions' into 'erbium-devel'
  Add motions for pal grasping pipeline
  See merge request robots/tiago_robot!62
* Add new motions for grasping
* Add motions for pal grasping pipeline
* Contributors: Victor Lopez

1.0.19 (2018-10-23)
-------------------
* Merge branch 'fix-gripper-camera-fps' into 'erbium-devel'
  set gripper camera to 15 fps
  See merge request robots/tiago_robot!59
* set gripper camera to 15 fps
* Contributors: Jordi Pages, Victor Lopez

1.0.18 (2018-09-19)
-------------------
* Remove wbc from joint mode blacklist
* Contributors: Victor Lopez

1.0.17 (2018-09-17)
-------------------
* Merge branch 'disable-speed-limit' into 'erbium-devel'
  Disable speed limit
  See merge request robots/tiago_robot!53
* removed commented limiters except sonar, discommented sonar limiter
* speed limit starts disabled
* Contributors: Procópio Stein, Victor Lopez

1.0.16 (2018-08-06)
-------------------

1.0.15 (2018-08-06)
-------------------

1.0.14 (2018-08-01)
-------------------
* Fix libuvc dependency name
* Contributors: Victor Lopez

1.0.13 (2018-08-01)
-------------------
* Merge branch 'add-end-effector-camera' into 'erbium-devel'
  add end-effector camera add-on required files
  See merge request robots/tiago_robot!55
* add end-effector camera add-on required files
* Contributors: Jordi Pages, Victor Lopez

1.0.12 (2018-07-30)
-------------------

1.0.11 (2018-07-13)
-------------------

1.0.10 (2018-07-10)
-------------------

1.0.9 (2018-05-24)
------------------

1.0.8 (2018-05-02)
------------------
* Merge branch 'deprecate_upload_tiago' into 'erbium-devel'
  deprecate upload_tiago & fix xacro warning --inorder
  See merge request robots/tiago_robot!42
* deprecate upload_tiago & fix xacro warning --inorder
* Contributors: Hilario Tome, Jeremie Deray

1.0.7 (2018-05-02)
------------------
* Merge branch 'motion-rename' into 'erbium-devel'
  Rename some end effector poses to generic names
  See merge request robots/tiago_robot!46
* Merge branch 'remove-chessboard' into 'erbium-devel'
  Remove chessboard, it's a separate entity now
  See merge request robots/tiago_robot!47
* Remove chessboard, it's a separate entity now
* Migrate offer as well
* Rename some end effector poses to generic names
* Contributors: Hilario Tome, Victor Lopez

1.0.6 (2018-04-10)
------------------

1.0.5 (2018-03-29)
------------------

1.0.4 (2018-03-26)
------------------
* Merge branch 'recover-chessboard-tiago' into 'erbium-devel'
  Recover chessboard tiago
  See merge request robots/tiago_robot!38
* Add missing tiago_steel_chessboard files
* Revert "remove unused files"
  This reverts commit e50aca81d55736b99e108bb90d681862be39c028.
* Contributors: Jordi Pages, Victor Lopez

1.0.3 (2018-03-16)
------------------

1.0.2 (2018-03-06)
------------------

1.0.1 (2018-02-22)
------------------

1.0.0 (2018-02-21)
------------------

0.0.46 (2018-02-20)
-------------------
* added extra wbc controller to mode blacklist and started to add local joint control configuration files
* Contributors: Hilario Tome

0.0.45 (2018-02-08)
-------------------

0.0.44 (2018-02-06)
-------------------
* fix force sensors axis
* Contributors: Jordi Pages

0.0.43 (2018-01-24)
-------------------
* add files for schunk-gripper based TIAGo
* update home and unfold_arm motions
* remove unused files
* Contributors: Jordi Pages

0.0.42 (2017-12-01)
-------------------
* Forward correct calibration files to openni2
* Add Copying of calibration files when launching xtion
* Contributors: Victor Lopez

0.0.41 (2017-10-31)
-------------------

0.0.40 (2017-10-27)
-------------------
* added support for absolute encoders
* Contributors: Hilario Tomé

0.0.39 (2017-07-12)
-------------------
* show throttled and downsampled point cloud
  And add buffer for sonars display
* Contributors: Jordi Pages

0.0.38 (2017-05-16)
-------------------
* Add configurations for Tiago Iron
* Contributors: davidfernandez

0.0.37 (2017-05-05)
-------------------
* disabled use_device_time from rgbd camera, to avoid tf errors
* Contributors: Procópio Stein

0.0.36 (2017-04-24)
-------------------
* added servoing_cmd_vel in twist_mux_topics
* Allow multiple Tiago to use the navigation stack
* Contributors: Procópio Stein, davidfernandez

0.0.35 (2016-12-21)
-------------------
* enable static tf
* Contributors: Jordi Pages

0.0.34 (2016-11-06)
-------------------

0.0.33 (2016-11-04)
-------------------

0.0.32 (2016-10-26)
-------------------
* add sonars visualizer
* Contributors: Jordi Pages

0.0.31 (2016-10-14)
-------------------
* 0.0.30
* Update changelog
* add myself as maintainer
* add myself as maintainer
* add arg to specifiy cmd_vel_out topic
* add missing run dependencies
* include the correct motions for steel version
* 0.0.29
* Update changelog
* Add the option of controlling tiago from the rviz joystick
* 0.0.28
* Update changelog
* Add gripper joints to exclude from planning
* 0.0.27
* Update changelog
* 0.0.26
* Update changelog
* put motions for titanium and steel separately
* 0.0.25
* Update changelog
* Add depth_registration to the sensor
* 0.0.24
* changelog
* Revert "set param ignore_read_errors true in ns ros_control_component"
  This reverts commit 244a8b98d6faeca71650903da68a0ab374f7c6cf.
* 0.0.23
* Update changelog
* 0.0.22
* Update changelog
* 0.0.21
* Update changelog
* 0.0.20
* Update changelog
* 0.0.19
* Update changelog
* 0.0.18
* changelog
* 0.0.17
* changelog
* add missing launch sonar_to_cloud
* 0.0.16
* Update changelog
* 0.0.15
* Update changelog
* set param ignore_read_errors true in ns ros_control_component
* 0.0.14
* Update changelog
* Add openni2_launch dependency
* 0.0.13
* Update changelog
* Contributors: Jeremie Deray, Jordi Pages, Sam Pfeiffer, Victor Lopez


0.0.30 (2016-10-13)
-------------------
* add myself as maintainer
* add myself as maintainer
* add arg to specifiy cmd_vel_out topic
* add missing run dependencies
* include the correct motions for steel version
* Contributors: Jordi Pages

0.0.29 (2016-07-28)
-------------------
* Add the option of controlling tiago from the rviz joystick
* Contributors: Victor Lopez

0.0.28 (2016-07-28)
-------------------
* Add gripper joints to exclude from planning
* Contributors: Victor Lopez

0.0.27 (2016-07-19)
-------------------

0.0.26 (2016-07-08)
-------------------
* put motions for titanium and steel separately
* Contributors: Jordi Pages

0.0.25 (2016-06-28)
-------------------
* Add depth_registration to the sensor
* Contributors: Sam Pfeiffer

0.0.24 (2016-06-15)
-------------------
* Revert "set param ignore_read_errors true in ns ros_control_component"
  This reverts commit 244a8b98d6faeca71650903da68a0ab374f7c6cf.
* Contributors: Jeremie Deray

0.0.23 (2016-06-15)
-------------------

0.0.22 (2016-06-15)
-------------------

0.0.21 (2016-06-15)
-------------------

0.0.20 (2016-06-14)
-------------------

0.0.19 (2016-06-14)
-------------------

0.0.18 (2016-06-14)
-------------------

0.0.17 (2016-06-13)
-------------------
* add missing launch sonar_to_cloud
* Contributors: Jeremie Deray

0.0.16 (2016-06-13)
-------------------

0.0.15 (2016-06-13)
-------------------
* set param ignore_read_errors true in ns ros_control_component
* Contributors: Jeremie Deray

0.0.14 (2016-06-10)
-------------------
* Add openni2_launch dependency
* Contributors: Victor Lopez

0.0.13 (2016-06-10)
-------------------

0.0.12 (2016-06-07)
-------------------
* Working head configuration for TIAGo
* Add transformation to correct FT readings
* Add hardware port of force torque
* Contributors: Jordan Palacios, Sam Pfeiffer

0.0.11 (2016-06-03)
-------------------
* Remove extra joints as the casters are not published anymore
* modify arm_6_joint position in home and unfold_arm
* add depth image visualizer
* 0.0.10
* Updated changelog
* Added joint mode blacklist to tiago hardware config
* 0.0.9
* Update changelog
* Making the incrementer server use the safe command topic
* Increase increments on head movements
* add new motions and modify existing ones
* 0.0.8
* Update changelog
* 0.0.7
* Update changelog
* 0.0.6
* Update changelogs
* Adding a stronger torque value
* Added blacklist parameter to tiago hardware
* Default dynamixel head for tiago 0, added as default because contains
  new dynamixel head necessary parameters
* 0.0.5
* Update changelog
* Adding new defaults for TIAGo
  Current limit controller for the wheels.
  Soften on effort values config for a specific robot.
* remap turbo reset
* tune joy min/max speed to reduce slipping
* remap joy speed in/decrease as they conflict with tiago torso
* spawn tiago speed_limit conf
* pmb2 twist_mux conf
* Re-Add marker detector launcher
* Add missing ports
* Add needed parameters from the base
* Fix ID of motor for tilt
* Remove battery monitor as its spamming and
  soon we'll have a real node giving battery information.
  Also the screen of the robot shows battery level
* Remove play_motion from launch to be started by pal_startup
* Add metadata of motions to make them show on webcommander
* Remove xtion from bringup launch, startup will take care of it
* Recovered fast hand motions
* updated poses for tiago0
* Add meta and motions that were deleted
* changed twist_mux out cmd topic
* Cleanup & add arm plannign group to play_motion
* Nicer home position
* Fix remapping to controller
* change torso limits and update motions
* add chessboard to dynamic foot print
* restrict lifter joint to go lower than 5 cm
  Take into account new mobile base covers that are 5 cm high
* Merge branch 'extra-joints' into 'cobalt-devel'
  Use generic pal_ros_control components
  Depends on:
  * [pal_ros_control/#5](https://gitlab/control/pal_ros_control/merge_requests/5) for handling dynamixels out-of-band of the actuators manager.
  * [ros_controllers/#15](https://gitlab/control/ros_controllers/merge_requests/15) for publishing dummy state for the caster joints on hardware deployments.
* Add configuration for dynamixel node
* add navigation displays
* add rviz configuration file
* Add extra_joints spec for joint state controller
  Only in hardware deployments: Load set of extra joints to be published as
  dummies by the joint_state_controller.
* Add battery_reporter to bringup
* Refs #11195. Add launch file for look_to_link
* Compatibility with pal_ros_control 0.4.3
  Update bringup configuration so TIAGo can use the generic ros_control component
  that is aware of extra joints not managed by ActuatorsManager (Dynamixel head
  joints).
* add launch file for lookToLink node
* Remove head from motion
* Take out planning group for arm
* Add open-close hand
* Remove head from motion description
* Corrected open and close motions (altho they are very slow)
* add line
* refs #11033. Define movement to unfold arm
* Add hand controller and wave motion
* Update home motion
* Enable motion planning and exclude hand joints from planning
* Contributors: Adolfo Rodriguez, Adolfo Rodriguez Tsouroukdissian, Bence Magyar, Hilario Tome, Jeremie Deray, Jordi Pages, Sam Pfeiffer, Sammy Pfeiffer, Victor Lopez, jordi.pages@pal-robotics.com

0.0.4 (2015-05-20)
------------------
* add motion to test the head
* Adding tiago_shadow, tiago with shadow lite hand (! no dependency on shadow packages on purpose!)
* Add head_xtion.launch to tiago.launch
* Contributors: Bence Magyar, Jordi Pages

0.0.3 (2015-04-15)
------------------
* add robot argument
* Contributors: Bence Magyar

0.0.2 (2015-04-15)
------------------
* Add incrementers for joy_teleop
* Move play_motion to controller launch files, update dependencies accordingly
* Add iron to startup
* Propagate robot argument to move_group
* moved to tiago_calibration package
* add step in pregrasp motion
* add motions for eye-hand calibration
* Add gripper open/close to motions
* Use steel and titanium tiago, launch files parametrized
* add tabletop pre-grasping pose
  add motion from extended arm on the side to raised pregrasping pose
* Add launch file for head xtion
* Change occureces of ant to pmb2
* Contributors: Bence Magyar, Jordi Pages

0.0.1 (2015-01-20)
------------------
* Add launch and dependency for dynamixel_node
* Add tiago_hardware.yaml file, upload in bringup and install rules for it
* Added launching of moveit on bringup
* Home motion = tucked
* Fix namespace
* Add play_motion and related config files
* Add dependencies
* Add deps to stuff used in launch files
* Add tiago_bringup and tiago_controller_configuration
* Contributors: Bence Magyar, Sammy Pfeiffer
