^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package map_file
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.6.3 (2018-03-06)
------------------

1.6.2 (2018-02-27)
------------------
* Update CHANGELOG
* Contributors: Yusuke FUJII

1.6.1 (2018-01-20)
------------------
* update CHANGELOG
* Contributors: Yusuke FUJII

1.6.0 (2017-12-11)
------------------
* Prepare release for 1.6.0
* use header.frame_id included in initialpose topic
* Initial modifications to feat_proj, tlr, context and vector_map loader, server and client to support different types of traffic signals
* Contributors: AMC, Yamato ANDO

1.5.1 (2017-09-25)
------------------
* Release/1.5.1 (`#816 <https://github.com/cpfl/autoware/issues/816>`_)
  * fix a build error by gcc version
  * fix build error for older indigo version
  * update changelog for v1.5.1
  * 1.5.1
* Contributors: Yusuke FUJII

1.5.0 (2017-09-21)
------------------
* Update changelog
* compilation issues
* added install targets
  changed finding pcl
  removed unneeded dependencies
* Contributors: Dejan Pangercic, Yusuke FUJII

1.4.0 (2017-08-04)
------------------
* version number must equal current release number so we can start releasing in the future
* added changelogs
* Contributors: Dejan Pangercic

1.3.1 (2017-07-16)
------------------

1.3.0 (2017-07-14)
------------------
* convert to autoware_msgs
* Contributors: YamatoAndo

1.2.0 (2017-06-07)
------------------
* fix circular-dependency
* Contributors: Shohei Fujii

1.1.2 (2017-02-27 23:10)
------------------------

1.1.1 (2017-02-27 22:25)
------------------------

1.1.0 (2017-02-24)
------------------

1.0.1 (2017-01-14)
------------------

1.0.0 (2016-12-22)
------------------
* Remove unnecessary error checks
* Delete map_file messages
* Refactoring
* Add error check for vector_map_loader
* Add download mode for vector_map_loader
* Have to be under_scored filename
* Rename wrong directory and filename
* Fix typos around map_db
* Add vector_map_loader corresponding to new road objects
* Add draft proposal of vector_map_loader
* Runtime Manager, update points_map_loader for SIGINT termination
* add const to errp read only parameter
* Runtime Manager Quick Start tab, fix Map load OK label
* Add module graph tool
* Fix for rosjava installed platform
  Some packages don't declare package dependencies correctly.
  This makes message jar files built failure.
* Rewrite points_map_loader
  Rewrite the entire main program.
  Delete a noisy debug message in library.
* Use pcd download thread too
  Existing callbacks use pcd download thread too.
* Add look ahead downloader
* Implement request queue to download pcd
* Are not DEBUG_PRINT
  These outputs are used by Runtime Manager.
* Move output of load message
* Fix handling of /pmap_stat
  Needn't buffer messages, should be lached.
  Add initialization code.
* Default variable is 1000 msec
* Fix update_rate
* Redesign map_downloader dialog
* Add ROS parameters for HTTP server
* Don't require initial position
* Delete file by the failure of download
  If libcurl fails to download, obtained file is deleted.
* Check HTTP response code
* Move std:ofstream::close
* Add digest access authentication
* Stop publishing messages of lane namespace
* Refactoring CMakeLists.txt
  Remove absolute paths by using cmake features and pkg-config.
* Use c++11 option instead of c++0x
  We can use newer compilers which support 'c++11' option
* Merge map_db with map_file.
* Fix road sign warning on Rviz
* Initial commit for public release
* Contributors: Shinpei Kato, Syohei YOSHIDA, USUDA Hisashi, kondoh, syouji
