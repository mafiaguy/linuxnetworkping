﻿# linuxnetworkping

This is a simple bash scipt used for network pinging

**HOW TO USE IT?**

Usage: ./pingh.sh [network]

Example: ./pingh.sh 192.168.1

Monitor log :- The core of the script is wrapped into endless while loop which is set to execute ping check every hour ( 3600 second ). Modify the script according to your needs. Remove endless while loop when you intend to use this script with cron scheduler.
