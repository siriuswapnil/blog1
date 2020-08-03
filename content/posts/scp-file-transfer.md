---
title: "File Transfer to virtual machine using SCP "
date: 2020-08-03T20:19:26+05:30
draft: false
---

Many a times, we need to transfer huge files from our host machine to a VM and the only interactive option seems to be using VirtualBox's shared folders feature or setting up USB transfer between the two machines. Both of these methods require the use of GuestAdditions which might be a bit complicated to setup sometimes.

Recently I had the need to transfer files from my Windows 10 host machine, to a VM running Ubuntu Server 18.04 running on Virtualbox. The file was 11 gigs in total, I just couldn't find a simple way to transfer the file.

Then I came to understand about SCP, which is a protocol for transferring files between computers. It uses SSH for data transfer, so the machines need to have their public and private keys set.A nice guide to setup keys using PuTTY in Windows can be found [[ https://linuxhint.com/ssh_virtualbox_guest ]] here.

Now once that is setup, all we need to do is use the folliwing command in a bash shell : 

```scp filename.jpg username@localip:/home/username/ ```

Here, the localip is important to set in VirtualBox. Under the VM Settings in VirtualBox, go to Networks, and select **Host Adapter**. A VirtualBox host adapter functions as a DHCP server to assign IP addresses (local) to VirtualBox Virtual Machines.The host machine and other VMs can connect to this VM using its internal IP which can be found using `ifconfig`, through ssh, or sftp. 

A handy tool to keep in mind.

Best
Swapnil