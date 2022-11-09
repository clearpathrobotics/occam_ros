^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package occam_ros
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Rename & reformat the changelog
* Update the STL so the orientation is correct, remove the roll/yaw transformations in the URDF
* Remove references to ${pi}, replace with the explicit number; pi is defined in the Jackal URDF, but doesn't exist on other platforms.
* Add the xacro ns to the include
* Contributors: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>

2.0.5
-----
* Add imgproc, stitch, rectify, and cloud nodes to support reproducing
  the Omni 60 and Omni Stereo pipelines offline from recorded data.
* Contributors: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>

2.0.4
-----

2.0.3
-----

2.0.2
-----

2.0.1
-----
* Republish config after set_parameters is invoked.
* Publish PointCloud2 rather than PointCloud.
* Include timestamp and sequence numbers with point cloud messages.
* Publish CameraInfo message for each sensor.
* Contributors: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>


2.0.0
-----
* Initial release
* Contributors: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
