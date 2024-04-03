^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ugv_sdk
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2024-04-03)
------------------
* swapped catking for ament
* [Release] bump verstion to 0.7.0
* Merge pull request `#47 <https://github.com/LCAS/ugv_sdk/issues/47>`_ from agilexrobotics/devel
  support titan robot
* support titan robot
* Merge pull request `#46 <https://github.com/LCAS/ugv_sdk/issues/46>`_ from westonrobot/bugfix-scout_bms
  src: fix scout bms feedback interface
* [Release] bump version to v0.6.0
* src: fix scout bms feedback interface
* Merge pull request `#45 <https://github.com/LCAS/ugv_sdk/issues/45>`_ from westonrobot/feature-bms_extend
  Feature bms extend
* cleanup: removed commented out code
* src: sample: fix ranger demo
* src: rename sensorstate to commonsensorstate
* src: cleanup sensor state msgs
* support bms extend struct
* add bms
* Merge pull request `#41 <https://github.com/LCAS/ugv_sdk/issues/41>`_ from westonrobot/feature-update_protocol
  Feature update protocol
* [Release] bump version to 0.5.0
* include: details: interface: update control mode enum to be consistent with newer robots
* Merge pull request `#40 <https://github.com/LCAS/ugv_sdk/issues/40>`_ from westonrobot/release-v0.4.0
  [Release]: bump version to 0.4.0
* [Release]: bump version to 0.4.0
* Merge pull request `#39 <https://github.com/LCAS/ugv_sdk/issues/39>`_ from westonrobot/feature-ranger_parking_mode
  ugv_sdk: ranger: implemented parking mode within sdk for Ranger Mini …
* ugv_sdk: ranger: implemented parking mode within sdk for Ranger Mini V2.0
* [Release] bump version to 0.3.0
* bms: moved bms from sensor group to core group
* CommonSensorStateMsgGroup: renamed to SensorStateMsgGroup
* Merge pull request `#38 <https://github.com/LCAS/ugv_sdk/issues/38>`_ from westonrobot/cleanup-interface_update
  Cleanup interface update
* parser: cleaned up parser base
* interface: cleaned up robot interfaces
* Merge pull request `#34 <https://github.com/LCAS/ugv_sdk/issues/34>`_ from westonrobot/bugfix-agilex_parser_v2
  agx_parser: fixed return value isse when not decoding successfully, t…
* agx_parser: fixed return value isse when not decoding successfully, to address pull request `#33 <https://github.com/LCAS/ugv_sdk/issues/33>`_
* Merge pull request `#31 <https://github.com/LCAS/ugv_sdk/issues/31>`_ from westonrobot/bugfix-ranger_base
  ranger: fixed bms voltage feedback
* ranger: fixed bms voltage feedback
* Merge pull request `#30 <https://github.com/LCAS/ugv_sdk/issues/30>`_ from westonrobot/feature-ranger_robot
  RangerRobot class for unified access to Ranger, Ranger Mini 1.0 and Ranger Mini 2.0
* ranger iface: tested working, revert include guard
* readme: updated sdk design section
* ranger iface: moved mini_v1 impl to ranger_base, added RangerBase class, to be tested on robot
* Merge pull request `#29 <https://github.com/LCAS/ugv_sdk/issues/29>`_ from westonrobot/feature-readme_update
  readme: updated readme about the sdk design
* readme: updated readme about the sdk design
* Merge pull request `#27 <https://github.com/LCAS/ugv_sdk/issues/27>`_ from westonrobot/feature-ranger_mini
  Feature ranger mini
* docs: updated readme and code comments at a few places
* side slip - fix command and feedback
* samples - edit for verbosity
* fix angular velocity - flip dir spinning mode
* motion state feedback - edit for ranger mini 1
* ranger_mini_v1: fixed spinning control mode, moved impl to cpp
* ranger_interface: fixed typo - kParallel
* package.xml: updated dependency and allow rosdep to install libasio-dev now
* ranger_robot: added cmath include
* agxv2 protocol - update for v5.7-5 firmware
* ranger: fixed ranger fw 0x271 msg decoding
* ranger_mini_v1: added a class to handle ranger mini v1 separately
* ranger: updated ranger interface to work with firmware v5.7.3
* ranger_interface: cleaned up ranger interface to keep consistency with other robots
* Merge pull request `#26 <https://github.com/LCAS/ugv_sdk/issues/26>`_ from westonrobot/bugfix-steering_angle_feedback
  protocol_v2: fixed steering angle feedback calculation
* protocol_v2: fixed steering angle feedback calculation
* ci: removed ubuntu18.04 runner as it's not supported by github anymore
* Merge pull request `#25 <https://github.com/LCAS/ugv_sdk/issues/25>`_ from agilexrobotics/enhancement-robot_base_support
  Enhancement: robot base support
* sample: update robot version demo to exit after function call
* submodule: fixed googletest submodule path
* enhancement: merged code changes from jason zhou, improved request version function implementation by rdu
* readme: minor adjustments to readme
* demo: renamed demo folder to sample, updated readme
* readme: updated readme
* ci: install git for ros builds
* ci: updated actions/checkout to v3 for ros builds
* ci: added more building test environments
* ci: added test for building on humble
* ci: updated container image to ros:melodic-robot
* Merge pull request `#21 <https://github.com/LCAS/ugv_sdk/issues/21>`_ from westonrobot/cleanup-fix_protocol_detector_typo
  typo: fixed spelling of protocol detector class name
* typo: fixed spelling of protocol detector class name
* hunter limits: apply changes from c31c4688be46f5a3d4c66ad15d43fa392d93562a in agilexrobotics/ugv_sdk
* protocol_v2: added implementation to bms basic and bms extended msg
* agilex_base: fixed memory issue related to can\_ interface
* Update README.md
  readme: fixed ci badge display
* Merge pull request `#17 <https://github.com/LCAS/ugv_sdk/issues/17>`_ from westonrobot/devel
  async_port: updated latest async_port impl from wrp_sdk
* async_port: updated latest async_port impl from wrp_sdk
* Merge pull request `#16 <https://github.com/LCAS/ugv_sdk/issues/16>`_ from ojura/main
  Fix position of catkin_package()
* Fix position of catkin_package()
  According to http://wiki.ros.org/catkin/CMakeLists.txt#Example, should be located before add_library/add_executable.
* memory: removed custom destructor for ScoutMiniOmniRobot (not necessary)
* ci: updated ros ci config to use main as default branch
* ci: removed ci tasks on next branch
* Merge pull request `#15 <https://github.com/LCAS/ugv_sdk/issues/15>`_ from westonrobot/next
  memory: fixed memory leak issue in scout mini omni wheel base
* memory: fixed memory leak issue in scout mini omni wheel base
* cmake: removed outdated cmake config for asio
* Merge branch 'next' into main
* interface: added header <stdexcept >to robot_interface.hpp for self-independence
* ci: updated ci config for github
* Merge branch 'next' of westonrobot.github.com:westonrobot/ugv_sdk into next
* removed outdated sample
* interface: changed void Connect() to bool Connect()
* cleanup: cleaned up a few comments and types
* agilex_types: added Agx prefix to types
* async_port: fixed resource release order issue in StopService()
* git: remove .editorconfig and added to ignore
* async_port: fixed return error in SetupPort()
* bugfix: fixed bunker base actuator state out-of-range error
* Merge pull request `#12 <https://github.com/LCAS/ugv_sdk/issues/12>`_ from chilatiao/next
  Added Bunker actuator state feedback, fixed an error in v1 protocol parsing (actuator feedback current)
* add bunker Actuator feedback function
* fixed current feedback bug in version 1
* Merge pull request `#1 <https://github.com/LCAS/ugv_sdk/issues/1>`_ from westonrobot/next
  Next
* updated ci, updated hunter set brake mode impl
* Merge pull request `#10 <https://github.com/LCAS/ugv_sdk/issues/10>`_ from chilatiao/next
  add brakeconfig function
* add SetBrakeMode function
* removed unsed func def
* added exception for invalid function calls from interface
* fixed hunter demo print issue
* added type check for parser in AgilexBase
* added scout mini omni support, updated scout related demo
* updated readme
* added time stamp to robot states
* renamed GetProtocolVersion() to GetParserProtocolVersion()
* moved serial connect to scout and tracer interface only
* renamed robot interface to robot common interface
* added hunter support
* added bunker robot support
* updated ranger base
* update tracer interface
* update missing status msg remove virtual function
* delete tracer_base.cpp
* moved state update function to agilex base class
* updated tracer interface
* removed tracer robot class, added rc state func for scout
* add tracer demo
* add tracer_robot
* update tracer_interface and tracer_base
* scout mini works
* fixed motion command
* added get protocol version api
* saved work on v1 protocol parser
* saved work
* added parser for scout
* saved work
* fixed function duplicated def issue
* saved work, updated code organization
* updated v1 protocol
* fixed scout_base decoding
* demo_scout_robot runs
* cleaned up folder
* saved work
* made scout_base to be class template
* saved work
* saved work
* saved work
* saved work
* cmake: enable asio old service
* cmake: fixing compile error in ubuntu 20.04
* ci: fixing libasio-dev dep
* merged async_port into ugv_sdk
* Merge pull request `#9 <https://github.com/LCAS/ugv_sdk/issues/9>`_ from wangzheqie/v2.x
  add motion mode feedback
* add motion mode feedback
* Merge pull request `#8 <https://github.com/LCAS/ugv_sdk/issues/8>`_ from wangzheqie/v2.x
  V2.x
* delete the log
* Merge branch 'v2.x' of https://github.com/westonrobot/ugv_sdk into v2.x
* read more motor data
* change set motion command function
* add ranger motion mode setting
* add ranger manuual
* scale the steer angle from 1000 to 100 times
* add some ranger protocol definition
* add doxyfile
* add ranger vehicle
* add ranger manuual
* scale the steer angle from 1000 to 100 times
* add some ranger protocol definition
* add doxyfile
* add ranger vehicle
* fixed typo in ci config
* more fix to git lab cpp ci setup
* updated github ci
* removed uart related description in readme
* more adjustments to readme
* updated readme
* updated README.md
* Merge branch 'update_protocol_v2.x' into 'v2.x'
  Update protocol v2.x
  See merge request westonrobot/public/ugv_sdk!1
* updated ci project path
* changed to make install instead of install .deb
* trying to resolve ci installation of .deb file
* resolved path issue in ci for cpp build
* enabled all ci images
* updated ci for xenial-cpp
* updated ci for kinetic-catkin-build
* fixed light command ctrl constant
* updated some path for app and demo for scout and tracer
* replaced wrp_io with async_port
* added in agx_protocol_v2
* moved ugv_sdk out from sub-folder
* removed wrp_io submodule
* updated can id for hunter
* updated scout code
* more cleanup to tracer_base
* tracer protocol v2.0 works
* saved work on protocol v2 for tracer
* removed uart support from protocol v2
* saved work on protocol v2, will remove uart support
* saved work on proto v2
* updated github action
* renamed folder with '_v2' back, disabled ci for ros temporarily
* V2.x (`#5 <https://github.com/LCAS/ugv_sdk/issues/5>`_)
  * added support of scout and hunter for protocol v2.0
* some code cleanup, started working on protocol v2.0
* updated to use lastest ci image
* sync with lastest wrp_io
* removed hunter_base to reduce ci time
* ci: removed requirements for higher version of cmake
* cleanedup ci setup and reverted back to using images from rduweston
* ci: offical ubuntu:20.04 gets stuck at geographic area selection
* ci: use ubuntu:18.04 and 20.04
* testing ci to use ubuntu:16.04 directly
* lowered cmake version requirements of ugv_sdk pkg'
* set ci to test build with cmake 3.5.1 in ubuntu 16.04
* updated readme on git submodule
* fixing ros ci on github
* udpated github ci
* Merge branch 'master' of https://gitlab.com/westonrobot/core/wrp_sdk
* updated readme and ci
* cleaned up ci config, removed test
* updated catkin config for ugv_sdk
* updated pcakge.xml for ugv_sdk
* updated wrp_io
* still trying to fix ci
* updated ci to update submodule manually
* major update to repo structure
* updated readme
* removed outdated line from readme
* updated readme
* updated readme
* increased cmake minimal version to be 3.13.0 to reflect actual requirement
* lowered cmake version to 3.5.1 for ubuntu 16.04
* updated readme about cmake
* added ubuntu 16.04 and ros kinetic to ci
* fixed typo in cmake/wrp_sdkConfig.cmake.in
* added en manual
* Merge branch 'master' of https://gitlab.com/westonrobot/core/wrp_sdk
* updated mobile base to use lastest serial communication impl
* saved work on timeout
* tested timeout
* added cmd timeout logic
* reverted back changes to function signature of serial rx callback func
* saved work on cmd timeout, not tested yet
* saved work on cmd timeout, not finished yet
* fixed can communication issue in mobile_base.cpp, tested with robot
* Merge branch 'asyncio' into 'master'
  Asyncio
  See merge request westonrobot/core/wrp_sdk!3
* updated ci permission
* added scout_base and hunter_base in ci config to test building dependency
* moved asio folder and tested catkin-isolated build
* install asio headers separately to the root include
* updated build type in cpp-ci config
* updated asio install structure
* updated to use updated asyncio implementation
* updated ci: added cpp build/test in ubuntu focal
* added noetic test
* updated cmakelists for ros build, added ci config to test both catkin_make and catkin_make_isolated
* update ci yml
* fixed docker image name
* added ci config to test building with catkin
* fixed ci test binary path issue
* fixed ci error
* updated ci config, test using different images
* Merge branch 'master' of https://gitlab.com/westonrobot/core/wrp_sdk
* added cppcheck config
* moved asyncio source files to folder src/asyncio, removed unused variable in scout_base.hpp
* Merge branch 'master' of https://github.com/westonrobot/wrp_sdk
* Merge branch 'PD_dev' into 'master'
  Fixed Scout demo bug
  See merge request westonrobot/core/wrp_sdk!1
* fixed scout demo bug, removed redecleration of fields in scout_base the hide mobile_base fields
* Update .gitlab-ci.yml
* Update .gitlab-ci.yml
* Update .gitlab-ci.yml
* Update .gitlab-ci.yml
* more cleanup in pkg info
* Update .gitlab-ci.yml to run test
* Update standalone-ci.yml
  added test run
* updated test config
* fixed cmake generated target path error
* updated cmake to put all executables in bin and libs in lib
* Update README.md
  Added badge for ROS CI
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
* Update ros-ci.yml
  trying to resolve catkin command not found issue
* Create ros-ci.yml
  add ci configuration for ros
* removed gitlab badge since it's not accessible from github mirror
* Update README.md, added gitlab pipeline badge
* Update README.md
  updated github workflow badge
* Update standalone-ci.yml
  updated standalone C++ flow name to be Cpp
* Update standalone-ci.yml
  changed workflow name to be standalone-ci from C/C++ CI
* Update README.md
  trying to add a ci action status badge
* updated action step name
* Update and rename c-cpp.yml to standalone-ci.yml
  merged pack and build into one step
* Update c-cpp.yml
* Update c-cpp.yml
  use sudo to install new pkgs
* Create c-cpp.yml
* updated readme: cleanup installation instructions
* Update .gitlab-ci.yml
* Update .gitlab-ci.yml
* Add .gitlab-ci.yml
* updated cmake configuration to build without ROS
* added scripts to setup/bringup can
* removed old names
* updated scout base to use class MobileBase
* removed unnecessary func declaration in hunter module
* updated readme
* make catkin optional
* added catkin lib config
* merged with next
* saved work
* saved work
* saved work
* saved work
* finished hunter HunterBase::SendRobotCmd()
* saved work
* created mobile base class
* more code cleanup
* code compiles with new structure
* commented out install
* saved work
* updated hunter max steering angle
* used const var to represent motor number
* updated hunter state variable name
* added catkin support
* Merge branch 'master' of https://bitbucket.org/westonrobotsoftware/wrp_sdk
* Merge branch 'master' of https://github.com/westonrobot/wrp_sdk
* removed irrlevant docs
* added tracer sdk
* Update README.md
* saved work
* code cleanup
* initial comit, ported scout_sdk and added hunter support
* Initial commit
* Contributors: Du Ruixiang, Hans Kurnia, Marc Hanheide, Matthew Ong, Pin Loon Lee, Ruixiang Du, Tan Pin Da, Your Name, agilexrobotics, chilatiao, hanskw-weston, hanskw4267, ihrabar, karthee-weston, lagrangeluo, pinloon.lee, rdu, wangzheqie, zhoups
