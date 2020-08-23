# freebsd-arpsec
customizable monitor for ARP changes, sending alerts to arbitrary API

Built for FreeBSD (12)

Currently runnging FreeBSd 12 with pkg:

arping                ARP level "ping" utility
arpwatch              Monitor arp & rarp requests
bash                  GNU Project's Bourne Again SHell
curl                  Command line tool and library for transferring data with URLs
sec                   Simple event (logs) correlator

Feel free to upgrade those packages, sec 2.8x should work fine.

See https://simple-evcorr.github.io/  and https://www.freshports.org/net-mgmt/arpwatch/


# setup alert output api
vim arp-api 


# Install

chmod +x install
./install
