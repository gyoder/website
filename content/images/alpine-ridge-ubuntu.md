---
title: "Alpine Ridge Ubuntu"
date: 2023-09-18T19:44:51-06:00
draft: false
---
## What is this image for
This image is for complete beginners who have very little experiance using Linux. This is also inteded to be used as a walkthrough for CyberPatriot clubs who need a basic and intresting Linux image to demonstrate. It can also be given as a resource for self learning.  

## Image Download

You can download the image [here](https://drive.google.com/file/d/10h6ObBbfTegMBQ_D0vdo7yeopBPfuYks/view?usp=sharing). Please attempt the image before watching the video. Almost all of the vulnerabilities are in the ReadMe of the image.

## Video Walkthrough
[There is a video walkthrough here.](https://www.youtube.com/embed/dN8Yczzix3s?si=0wKJJTYQdHMC2JPm) You should be able to get most of the points in the image with the ReadMe and Google if you are a complete beginner. This is mostly for finding the vulnerabilities that you have missed after attemting it and learning why they are vulnerabilities.

## Useful Resources
[Linux, Visually](https://youtube.com/playlist?list=PLcn9NsWbb8s4wQrX0Qi5G4kRifQHxCV9-&si=SxfXYgGNyfqI3Nz8)
[Linux, Visually: Package Management](https://youtu.be/Bd93or6XaLg?si=PB2LXSpSkLm2DcKc)
[Linux, Visually: SSH](https://youtu.be/csamazU4rjY?si=gGdTxeZrR3ZPLGdR)
[Linux, Visually: Ports and Processes](https://youtu.be/u6KYekiWKzM?si=aHT2IvsGRqLiIrXd)
[60 Linux commands to know](https://youtu.be/gd7BXuUQ91w?si=6SljmE54Tzw_Nx7m)
[Introducing the Linux Terminal](https://youtu.be/VbEx7B_PTOE?t=322&si=qBbdOsQ0HIRvQB5I)
[Linux for Hackers](https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&si=b9rF2Euwlwiyf4aN)

## Commands Used

These are listed in order of apperence in the video.

`id <username>` find UID of user

`cat <path/to/file>` read file contents

`md5sum <path/to/file>` Find MD5 Hash of File

`hostname` Hostname of the Computer

`sudo useradd <username>` add a user

`sudo userdel <username>` remove a user

`sudo usermod -aG <group> <username>` add a user to group

`sudo nano <path/to/file>` Open a file in nano text editor

`sudo nano /etc/login.defs` Edit the login.defs file

`sudo ufw enable` enable the firewall

`sudo ufw allow <protocol or port>` allow a certain protocol or port through the firewall

`sudo ufw allow ssh` allow ssh through the firewall

`sudo apt purge <application name>` delete an app and all of its configs

`sudo apt remove <application name>` delete an app but keep its configs

`sudo apt-mark showmanual` show all manually installed apps

`sudo snap list` show apps installed with snap

`sudo snap removed` remove apps installed with snap

`tree` show a file tree

`sudo service --status-all` show all services that are running or not running

`sudo systemctl stop <service>` stop a service

`sudo systemctl disable <service>` disable a service from running on startup

`crontab -e` edit crontabs