Next Release (0.4)
==================

Release 0.3
===========
Features
--------
* Add M2Eclipse lifecycle mapping metadata for Eclipse IDE.
* Strips plugin.xml and plugin-help.xml files generated by maven-plugin-tools.
* [#3](https://github.com/Zlika/reproducible-build-maven-plugin/pull/3): Allow standalone usage of strip-jar - [@jumapico](https://github.com/jumapico).

Non-functional changes
----------------------
* Upgrade commons-compress to avoid reflection hack.

Release 0.2
===========
Bug Fixes
---------
* Fix NPE if target folder does not exist.

Features
--------
* New strip-jaxb goal to normalize ObjectFactory.java files produced by JAXB/xjc.

Release 0.1
===========
First release for tests.
Features
--------
* Sorts ZIP entries by name.
* Sets file timestamps in ZIP entries to 0.
* Removes timestamps, user name and tool versions in MANIFEST.MF.
* Removes timestamp in pom.properties.