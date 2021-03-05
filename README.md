# libnfs [![Build Status](https://travis-ci.org/cholcombe973/libnfs.svg?branch=master)](https://travis-ci.org/cholcombe973/libnfs)
Safe NFS bindings to build NFS clients in Rust
[libnfs](https://github.com/sahlberg/libnfs) rust bindings

NFS in userspace.

Note to users:
  Depending on your system you may need to install some extra libraries for this to link properly.
  Here's what I used on debian 10 (buster):

```
dpkg -l | grep -i libnfs
ii libnfs-dev:amd64 3.0.0-2 amd64 NFS client library (development files)
ii libnfs12:amd64 3.0.0-2 amd64 NFS client library (shared library)
```
