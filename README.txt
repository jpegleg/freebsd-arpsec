# freebsd-arpsec
customizable monitor for ARP changes, sending alerts to arbitrary API

Built for FreeBSD (12)

Currently runnging FreeBSd 12 with pkg:

arping-2.19                    ARP level "ping" utility
arpwatch-3.1                   Monitor arp & rarp requests
bash-5.0.11                    GNU Project's Bourne Again SHell
curl-7.67.0                    Command line tool and library for transferring data with URLs
sec-2.7.12_1                   Simple event (logs) correlator

Feel free to upgrade those packages, sec 2.8x should work fine.

See https://simple-evcorr.github.io/  and https://www.freshports.org/net-mgmt/arpwatch/


# setup alert output api
vim arp-api 


# Install

chmod +x install
./install
