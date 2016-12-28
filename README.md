nano helper
===========

[![Version][Version image]][Releases]

This is the [Buildroot container](https://github.com/Docker-nano/Buildroot) workflow helper script that is included as a [Git submodule](http://git-scm.com/book/en/v2/Git-Tools-Submodules) in most [Buildroot](https://github.com/Docker-nano/Buildroot)-based products.

Usage
-----

* `./nano help` – Display usage information.
* `./nano build all` - Build all of the following targets.
* `./nano build container` – Build `Dockerfile`.
* `./nano build rootfs` - Build `rootfs.tar.xz` image.
* `./nano run [command [args...]]` – Run container, optionally with the specified command and arguments.
* `./nano resume` – Resume container.
* `./nano pull` – Pull all of the following targets from the container to the host.
* `./nano pull config` – Pull Buildroot configuration.
* `./nano pull patches` – Pull Buildroot patches from `~/buildroot/patches`. 
* `./nano pull rootfs` – Pull generated `rootfs.tar.xz` image.

Changes
-------

See [changes.md](meta/changes.md).

  [Releases]: https://github.com/Docker-nano/nano/releases
  [Version image]: http://img.shields.io/github/tag/Docker-nano/nano.svg "Latest version"
