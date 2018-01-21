# Python3-Wine

![license](https://img.shields.io/github/license/webcomics/pywine.svg)
![Maintenance](https://img.shields.io/maintenance/yes/2018.svg)
![Docker Automated build](https://img.shields.io/docker/automated/tobix/pywine.svg)
[![](https://images.microbadger.com/badges/image/tobix/pywine.svg)](https://microbadger.com/images/tobix/pywine "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/commit/tobix/pywine.svg)](https://microbadger.com/images/tobix/pywine "Get your own commit badge on microbadger.com")

This is a docker container to help building Python applications in Wine. It
installs Python, PyInstaller and some extensions to be abel to build "native"
Windows applications. It also installs UPX, so PyInstaller can use it to
compress binaries.

This is currently installed:

 * Python 3.6.4
 * pbr
 * PyInstaller
