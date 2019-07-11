#!/bin/bash
sudo find /opt/backup_allVM/ -name "*.*" -mtime +14 -exec rm -Rf {} \;
#Script runs by cron and allow to keep vmdumps not older then 14 days in /var/lib/vz/dump/ in local server
