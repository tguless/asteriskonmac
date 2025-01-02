# asteriskonmac
Running asterisk on a mac

Install docker

Just run go.sh

Docker compose will build a base image that has:

Debian 12.8 (bookworm)

Asterisk 22.1.0

BCG729 1.0.4

SPANDSP 20180108

And will use the base image to stand up FreePBX:

FreePBX 17.0-latest-EDGE

Known Issues: 

https://community.freepbx.org/t/installation-fails/103298

Related Repos: 

https://github.com/tguless/asterisk

https://github.com/tguless/freepbx