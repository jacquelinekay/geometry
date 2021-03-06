^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package eigen_conversions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.11.6 (2015-03-25)
-------------------

1.11.5 (2015-03-17)
-------------------

1.11.4 (2014-12-23)
-------------------

1.11.3 (2014-05-07)
-------------------

1.11.2 (2014-02-25)
-------------------
* alphabetization and updating cmake to find Eigen
* Contributors: Tully Foote

1.11.1 (2014-02-23)
-------------------
* add dep on cmake_modules for finding eigen
* Contributors: Ioan Sucan

1.11.0 (2014-02-14)
-------------------
* fixed Eigen-KDL 3D Vector conversion functions
* Contributors: fevb

1.10.8 (2014-02-01)
-------------------

1.10.7 (2013-12-27)
-------------------

1.10.6 (2013-08-28)
-------------------

1.10.5 (2013-07-19)
-------------------

1.10.4 (2013-07-11)
-------------------

1.10.3 (2013-07-09)
-------------------

1.10.2 (2013-07-09)
-------------------

1.10.1 (2013-07-05)
-------------------

1.10.0 (2013-07-05)
-------------------

1.9.31 (2013-04-18 18:16)
-------------------------
* add link directories

1.9.30 (2013-04-18 16:26)
-------------------------
* Fixes `#11 <https://github.com/ros/geometry/issues/11>`_: orocos_kdl now has cmake rules oroco-kdl
  update cmake to use orocos_kdl as plain cmake package instead of catkin package
  Signed-off-by: Ruben Smits <ruben.smits@intermodalics.eu>

1.9.29 (2013-01-13)
-------------------

1.9.28 (2013-01-02)
-------------------

1.9.27 (2012-12-21)
-------------------

1.9.26 (2012-12-14)
-------------------
* add missing dep to catkin

1.9.25 (2012-12-13)
-------------------

1.9.24 (2012-12-11)
-------------------
* Version 1.9.24
* Fixes to CMakeLists.txt's while building from source

1.9.23 (2012-11-22)
-------------------
* Releaseing version 1.9.23

1.9.22 (2012-11-04 09:14)
-------------------------

1.9.21 (2012-11-04 01:19)
-------------------------

1.9.20 (2012-11-02)
-------------------

1.9.19 (2012-10-31)
-------------------
* Removed deprecated 'brief' attribute from <description> tags.

1.9.18 (2012-10-16)
-------------------

1.9.17 (2012-10-02)
-------------------
* fix several dependency issues

1.9.16 (2012-09-29)
-------------------
* adding geometry metapackage and updating to 1.9.16

1.9.15 (2012-09-30)
-------------------
* fix a few dependency/catkin problems
* remove old API files
* comply to the new catkin API

1.9.14 (2012-09-18)
-------------------

1.9.13 (2012-09-17)
-------------------

1.9.12 (2012-09-16)
-------------------

1.9.11 (2012-09-14 22:49)
-------------------------

1.9.10 (2012-09-14 22:30)
-------------------------

1.9.9 (2012-09-11)
------------------
* update depends
* minor patches for new build system

1.9.8 (2012-09-03)
------------------

1.9.7 (2012-08-10 12:19)
------------------------
* minor build fixes
* completed set of eigen conversions; added KDL conversions
* adding additional conversion functions

1.9.6 (2012-08-02 19:59)
------------------------

1.9.5 (2012-08-02 19:48)
------------------------

1.9.4 (2012-08-02 18:29)
------------------------

1.9.3 (2012-08-02 18:28)
------------------------
* forgot to install some things
* also using DEPENDS

1.9.2 (2012-08-01 21:05)
------------------------

1.9.1 (2012-08-01 19:16)
------------------------
* install manifest.xml

1.9.0 (2012-08-01 18:52)
------------------------
* catkin build system
* added some additional conversion routines between eigen and messages
* removing dependency on eigen package
* compiling with eigen3
* missed a rename
* more extensive search
* applying patch from sed script for eigen3 compatability
* Moving eigen_conversions from sandbox.
