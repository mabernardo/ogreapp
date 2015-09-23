# ogreapp
An Ogre (http://www.ogre3d.org/) tutorials and study.

##Prerequisites
You must have Ogre SDK installed in your system to build this application, more information on how to install Ogre in your system can be found in the Ogre Wiki:

http://www.ogre3d.org/tikiwiki/tiki-index.php?page=Installing+the+Ogre+SDK


##Building
This application user CMake as its build system.
CMake is available from http://www.cmake.org (Resources -> Downloads).

If you are on a Linux system, chances are high that your distributor offers a package for CMake. You need a CMake
version >= 2.6.
For Ubuntu, type the following in a console to install CMake:

`sudo apt-get install cmake-gui`

You may have to edit the CMakeLists.txt to change the paths to where the Ogre libraries are installed.

* Start cmake-gui and choose source directory and build directory. 
* Click 'Configure' and choose the makefile generator of your preference.
* After 'Configure' click once on 'Generate' to get a working makefile project.

More information on how to setup and build the application on a specific platform or development tool can be found in Ogre Wiki:

http://www.ogre3d.org/tikiwiki/tiki-index.php?page=Setting+Up+An+Application
