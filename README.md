# CTC

CERT Team Computer

A Citizen's Emergengy Response Team (CERT) is activated when a major disaster overwhelms the first responders. A CERT team computer is a tiny Linux-based computer intended to support a CERT team in the field. This repository describes the hardware, Linux distro customizations, and specialized software applications that comprise the CTC. The principle unique functionality is the Ham radio interface. This project in intended to provide all of the information needed to create a CTC.

Hardare can be any tiny Linux computer that has audio I/O and WiFi. This project initially uses the NanoPi Duo. We describe how to construct a case and cabling to turn this into a usable rugged computer.

The initial Linux distro is the Sun8xi distro provided for the NanoPi Duo. the project describes how to customize it by dropping some app and adding others. In addition to app in the Sun8xi repository, the CTC uses s few apps that reside elswhere: The Direwolf AX.25 sound modem, the CHIRP radio programming system, and the OpenStreetMap map software.

Software unique to the CTC resides in this repository. The initial app is call WebPost. WebPost is a web server and supporting HTML pages to serve. It allows a user to connect to a CTC via a LAN and use a browser to interact with a remote AX.25 BBS.
