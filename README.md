# Gentoo Setup Script

## This Script automaticly setup the Gentoo OS(AMD64)

This script only setup **amd64 Gentoo OS**

## How to run Gentoo-Setup Script 

Start the gentoo amd64 image and enter this command.

```
boot: gentoo dopcmcia
```

Before running the script, must be configure the network.

Configure the network: https://wiki.gentoo.org/wiki/Handbook:AMD64/Installation/Networking

End of the network config. copy the script file on Gentoo. 
Gentoo has not a packet manager yet. Because of we can't clone the script on Gentoo.
But Gentoo has a shh service. If u want try to copy script with **scp** command


If u want to use ssh first restart ssh service. Run this command on gentoo machine 
```
/etc/init.d/sshd restart
```
Run the scrpit after the copy.
```
./gentoo-setup.sh
```
Script first a ask some question 
