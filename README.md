# 4620Project

The idea for this project is to be a defensive security utility to be able to detect and possibly act on 
active sniffers on a network. This does not go deep into raw socket programming but is more of a bash scripting
project that uses networking and other Linux CLI tools for a backend.

The packet-sniffing detection script uses ARP packets to send to the target and uses responses and timing to determine if the 
host is likely in promiscuous mode. You can read more about it [here](https://www.securityfriday.com/promiscuous_detection_01.pdf).

