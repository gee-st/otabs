# otabs

<p align="center">
  <img src="misc/img/white-logo-BhQWk_Ow.svg"/>
</p>

OTA software update system for automotive Embedded Linux systems.

## System components

- Software provider host: provides software remotely through FTP
- Software receiver: Raspberry Pi machine running a QNX image
- Target machine: machine that receives updated Linux image (in this case also a Raspberry Pi)
- FTP: communication host and receiver
- CRC: integrity check for received files
- SOME/IP: communication between receiver and target
