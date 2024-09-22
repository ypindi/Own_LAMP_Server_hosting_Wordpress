# Own LAMP Server on Rocky Linux 8.10

## 1 Introduction
This Project aims to create a LAMP server out of a virtual disk image (VDI). This VDI has a configuration file for Virtual Machine (VM) box - native linux virtualization environment. 
I configured the RAM, ROM, CPU, and network card (with RAM, ROM) on our laptop / personal machine. Once that boots, the OS itself will
have different RAM, CPU, and network Card. The network card (or the network
interface) right now is not configured - so we will have to configure it. The network
configuration is not very easy on linux. Different linux distributions have different ways to
configure the network cards. It is not complicated but it is different for different linux
systems (because all systems are different flavours of distributions).

## 2 Server
The Server has been uploaded on the Cloud. You can find it in the below link:
```
OVF Format: https://cloud.htw-berlin.de/f/147454317

OVA Format: https://cloud.htw-berlin.de/f/147477450
```

