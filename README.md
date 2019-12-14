This repository is building image in Docker, It is basing SO Ubuntu 18.04 with novnc and vnc

===Download Image===

docker pull arcralch07/ubuntu_novnc:18.04

===Run Container===

docker run -d -p 6901:6901 --name ubutu_novnc arcralch07/ubuntu_novnc:18.04

or

Open port 5901 of vncviewer

docker run -d -p 6901:6901 -p 5901:5901 --name ubutu_novnc arcralch07/ubuntu_novnc:18.04

====Run Container====

You will request a password at the beginning of the section is "vncqa" for enter.

Integrated with new resolution graphic 1280x630. It visualition in navegador web.
