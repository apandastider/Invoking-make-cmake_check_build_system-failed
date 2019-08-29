-- Could not find the required component 'qt_build'. The following CMake error indicates that you either need to install the package with the same name or change your environment so that it can be found.
CMake Error at /opt/ros/kinetic/share/catkin/cmake/catkinConfig.cmake:83 (find_package):
  Could not find a package configuration file provided by "qt_build" with any
  of the following names:

    qt_buildConfig.cmake
    qt_build-config.cmake

  Add the installation prefix of "qt_build" to CMAKE_PREFIX_PATH or set
  "qt_build_DIR" to a directory containing one of the above files.  If
  "qt_build" provides a separate development package or SDK, be sure it has
  been installed.
Call Stack (most recent call first):
  ROBOTIS-MANIPULATOR-H/manipulator_h_gui/CMakeLists.txt:13 (find_package)


-- Configuring incomplete, errors occurred!
See also "/home/apandastider/catkin_ws/build/CMakeFiles/CMakeOutput.log".
See also "/home/apandastider/catkin_ws/build/CMakeFiles/CMakeError.log".
Makefile:318: recipe for target 'cmake_check_build_system' failed
make: *** [cmake_check_build_system] Error 1
Invoking "make cmake_check_build_system" failed
