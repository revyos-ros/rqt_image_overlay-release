^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rqt_image_overlay
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.8 (2022-09-26)
------------------
* Correctly map ImageManager list model index to topic vector (#47 <https://github.com/ros-sports/rqt_image_overlay/issues/47>)
* Contributors: Kenji Brameld, Marcel Zeilinger

0.0.7 (2022-08-07)
------------------
* use sensor qos for overlays too
* Contributors: Kenji Brameld

0.0.6 (2022-06-15)
------------------
* fix up test
* change theora transport dependency to compressed transport
* Contributors: Kenji Brameld

0.0.5 (2022-03-12)
------------------
* remove unused dependencies
* add layer color selection feature
* fix deprecation warning
* Contributors: Kenji Brameld

0.0.4 (2022-03-02)
------------------

* Add message collection window, and synchronize image and layers using header timestamp if available
* use present tense for getReceivedStatus
* implement overlay using msg_storage and use mutexes to handle multithreading
* start implementing msg storage
* add msg storage class
* Contributors: Kenji Brameld

0.0.3 (2022-02-26)
------------------
* Replace #!/usr/bin/env python with #!/usr/bin/env python3
* Delete the subscription if there are no publishers on the subscribed topic when refreshed
* Handle fake transports that end with a transport ending, but aren't actually image topics
* Handle multiple image transports
* Convert type used to store image topic from std::string to rqt_image_overlay::ImageTopic
* Use sensor qos for image subscription
* Contributors: Kenji Brameld, Scott K Logan, wep21

0.0.2 (2022-01-29)
------------------
* adapt to new changes in cpplint about using a leading "./" in include statements
* Contributors: ijnek

0.0.1 (2022-01-08)
------------------
* Initial release
* Contributors: ijnek
