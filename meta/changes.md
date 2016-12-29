nano helper changes
===================

Version 2.0.1
-------------

Date: 28th December 2016.

* Fixed run operation to not spawn interactive process when STDIN is not a TTY.

Version 2.0.0
-------------

Date: 28th December 2016.

* Added container, rootfs and all targets to build operation.
* Added command and arguments parameters to run operation.

### Breaking changes

Build operation now requires a target specifier. Not specifying a target outputs usage instructions.

Version 1.1.1
-------------

Date: 28th December 2016.

* Really fixed containerExists function (previously acted as containerRunning).

Version 1.1.0
-------------

Date: 17th November 2015.

* Fixed containerExists function for newer Docker versions.

Version 1.0.1
-------------

Date: 18th November 2014.

* Fixed folder permissions when pulling targets with `sudo`.
* Added error checking when loading `settings`.
* Added `pull` usage on unrecognised target.

Version 1.0.0
-------------

Date: 11th November 2014.

* Added help, build, run, resume, pull config/patches/rootfs operations.
