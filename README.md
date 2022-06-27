# Mysql Backup With Retention


This is a simple Bash script to take desired MySQL backup with a retention policy(daily, monthly, and weekly). 

Script configuration
============================

1. Copy the script to your server and edit the below given values. here i am copy the script to /usr/local/scripts
   
  THE_PATH (line 5), This is the path of backup
  db (line 12), Here you need to mention the DB name that you want to take backup
  
2. Add the cron job and select the time when you want the script to run, here i am run the script at neight 1 o'clock.
   0 1 * * * /bin/bash /usr/local/scripts/script_name.sh

