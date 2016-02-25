docker-boinc
============

Something to run World Community Grid tasks with.

### Usage:

    docker run -d ozzyjohnson/boinc \
      -attach_project www.worldcommunitygrid.org \
                      949787_15ca7825fb58f9d01b6ad15221c3f048

TODO
- [ ] change base OS to alpine linux to reduce image size (http://boinc.berkeley.edu/wiki/Installing_on_Linux)
