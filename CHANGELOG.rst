^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package flexbe_app
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.3 (2018-12-19)
------------------
* Merge remote-tracking branch 'origin/develop'
* Add cmake dependency on rostest
* Merge remote-tracking branch 'origin/master' into develop
* Contributors: Philipp Schillinger

2.1.2 (2018-12-18)
------------------
* Merge remote-tracking branch 'origin/develop'
* Switch to curl for nwjs download
* Contributors: Philipp Schillinger

2.1.1 (2018-12-18)
------------------
* Merge remote-tracking branch 'origin/develop'
* Fix #29: Use correct statelib call to open source code
* Contributors: Philipp Schillinger

2.1.0 (2018-12-01)
------------------
* Initial ROS release
* Contributors: Philipp Schillinger

2.0.11 (2018-12-01)
-------------------
* Merge remote-tracking branch 'origin/develop'
* Add shortcut support for sourcing
* Fix `#8 <https://github.com/FlexBE/flexbe_app/issues/8>`_: Correct typo in synthesis feedback
* Fix `#15 <https://github.com/FlexBE/flexbe_app/issues/15>`_: Correctly handle duplicate state class definitions
* Merge remote-tracking branch 'origin/develop'
* Merge remote-tracking branch 'origin/master' into develop
* Hide detailed install output
* Increment nwjs version
* Merge branch 'feature/add_tests' into develop
* Update manifest
* Create .travis.yml
* Set test_report to executable
* Add test routine
* Merge remote-tracking branch 'origin/feature/install_support' into develop
* Fix `#25 <https://github.com/FlexBE/flexbe_app/issues/25>`_: Use python path instead of package path
* Update manifest
* Prevent behavior modifications when loading from install space
* Move package python path out of package parser
* Fixes issue `#24 <https://github.com/FlexBE/flexbe_app/issues/24>`_ using first proposed solution.
* implementing ROS.getPackagePythonPath similarly to IO.PackageParser's getPythonPath
* Use package path for manual section update
* Merge branch 'tu-darmstadt-ros-pkg-master' into feature/install_support
* Adjust catkin install paths for rospack use
* Merge branch 'master' of https://github.com/tu-darmstadt-ros-pkg/flexbe_app into tu-darmstadt-ros-pkg-master
  Conflicts:
  CMakeLists.txt
  bin/run_app
  src/io/io_behaviorloader.js
  src/io/io_packageparser.js
* Parse installed packages (see `#19 <https://github.com/FlexBE/flexbe_app/issues/19>`_)
* Merge pull request `#18 <https://github.com/FlexBE/flexbe_app/issues/18>`_ from meyerj/feature/install-rules
  Add cmake install rules and use rospack to find nw executable
* fix state path to correct generated import statements
* make locating behavior files work in install and devel setups
* make behaviors work in install space
* Add cmake install rules and use rospack to find nw executable
* Fix `#14 <https://github.com/FlexBE/flexbe_app/issues/14>`_: Update state definition only for python files but any event type
* Merge pull request `#13 <https://github.com/FlexBE/flexbe_app/issues/13>`_ from FlexBE/feature/state_update
  Update states when source code changes (see `#10 <https://github.com/FlexBE/flexbe_app/issues/10>`_)
* Update manifest
* Update states when source code changes (see `#10 <https://github.com/FlexBE/flexbe_app/issues/10>`_)
* Contributors: Dorian Scholz, Dustin Gooding, Johannes Meyer, Philipp Schillinger

2.0.10 (2018-11-24)
-------------------
* Merge remote-tracking branch 'origin/develop'
* Contributors: Philipp Schillinger

2.0.6 (2018-03-04)
------------------
* Merge remote-tracking branch 'origin/develop'
* Make behavior name processing more robust (fix `team-vigir/flexbe_behavior_engine#51 <https://github.com/team-vigir/flexbe_behavior_engine/issues/51>`_)
* Update manifest
* Fix `#12 <https://github.com/FlexBE/flexbe_app/issues/12>`_: Improved responsiveness of connecting transitions
* Fix `#9 <https://github.com/FlexBE/flexbe_app/issues/9>`_: Correctly reset transitions to outcomes and add removal
* Remove requirement of keyring access
* Merge remote-tracking branch 'origin/feature/autoinstall' into develop
* Merge remote-tracking branch 'origin/master' into feature/autoinstall
* Install nwjs on running catkin build
* Removed nwjs files and added install to first execution
* Contributors: Philipp Schillinger

2.0.5 (2017-10-01)
------------------
* Several minor additions and fixes
* Update manifest
* Can select to use default values for behavior input keys (see `team-vigir/flexbe_behavior_engine#38 <https://github.com/team-vigir/flexbe_behavior_engine/issues/38>`_)
* Fix `#7 <https://github.com/FlexBE/flexbe_app/issues/7>`_: Whitespace before first state parameter now optional
* Fix `#6 <https://github.com/FlexBE/flexbe_app/issues/6>`_: Compare float value not int for parameter value bounds
* Enable utf-8 encoding in generated behaviors
* Fix `#5 <https://github.com/FlexBE/flexbe_app/issues/5>`_: Negative values for numeric parameters
* Added support for state and behavior packages in editor
* Contributors: Philipp Schillinger

2.0.2 (2017-04-23)
------------------
* Update manifest
* Add button to view state source code
* Fix: use correct attribute to determine drag indicator width
* Fix: stop that states jump to zero if move icon is only clicked
* Fix: creating a new behavior fails when onboard engine is running (see `#4 <https://github.com/FlexBE/flexbe_app/issues/4>`_)
* Fix: creating a new behavior fails without error log (see `#4 <https://github.com/FlexBE/flexbe_app/issues/4>`_)
* Fixed missing yaml import in ROS action client
* Support opening multiple windows
* Only update drawing on outcome request if available (fixes `#2 <https://github.com/FlexBE/flexbe_app/issues/2>`_)
* Contributors: Philipp Schillinger

2.0.1 (2017-02-25)
------------------
* Update manifest
* Fix to avoid placement of new states under container path label
* Fixed function reference for visual update of autonomy level change
* Removed deprecated roslib import
* Contributors: Philipp Schillinger

2.0.0 (2017-01-16)
------------------
* Update README.md
* Made required files executable
* Initial commit of software
* Update README.md
* Initial commit
* Contributors: Philipp Schillinger
