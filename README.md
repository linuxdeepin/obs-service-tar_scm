# tar_scm (OBS source service) [![Build Status](https://travis-ci.org/openSUSE/obs-service-tar_scm.png?branch=master)](https://travis-ci.org/openSUSE/obs-service-tar_scm)

This is the git repository for [openSUSE:Tools/obs-service-tar_scm](https://build.opensuse.org/package/show/openSUSE:Tools/obs-service-tar_scm).
The authoritative source is:

* https://github.com/openSUSE/obs-service-tar_scm

The files in this top-level directory need to be installed using the following:

    mkdir -p /usr/lib/obs/service
    mkdir -p /etc/obs/services
    install -m 0755 tar_scm /usr/lib/obs/service
    install -m 0644 tar_scm.service /usr/lib/obs/service
    install -m 0644 tar_scm.rc /etc/obs/services/tar_scm

## Test suite

See the [TESTING.md](TESTING.md) file.

## Contributions

See the [CONTRIBUTING.md](CONTRIBUTING.md) file.
