# Mysql Backup With Retention


This is a simple Bash script to take desired MySQL DB backup with a retention policy(daily, monthly, and weekly). 

Script configuration
============================

Copy the script to your server and edit the below given values. here i am copy the script to /usr/local/scripts. <br>
  db (line 12), Here you need to mention the DB name that you want to take backup.<br>
  line 5 - backup path.
  
Add the cron job and select the time when you want the script to run, here i am run the script at neight 1 o'clock.<br>
   0 1 * * * /bin/bash /usr/local/scripts/script.sh
   
   
You can change the monthly and weekly backup days by editing lines 9 and 10.


