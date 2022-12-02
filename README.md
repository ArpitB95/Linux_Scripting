# Linux_Scripting


## Basic script

<img width="328" alt="script1" src="https://user-images.githubusercontent.com/110182832/205352412-d22eb768-49ea-411a-9578-7f6346c600b3.png">


## if_else

<img width="398" alt="if-else" src="https://user-images.githubusercontent.com/110182832/205352512-e6eb22e4-30dc-4062-affb-be23070f4b4d.png">


## if_elif

<img width="368" alt="if-elif" src="https://user-images.githubusercontent.com/110182832/205352553-4882db73-19d4-41f4-8049-fa898e4ab592.png">

## loop


<img width="367" alt="loops" src="https://user-images.githubusercontent.com/110182832/205352593-0a3366ec-8f32-4ee8-99ac-a158f73e800e.png">




## Script to check disk space/usage

<img width="850" alt="Linux script_check_harddisk" src="https://user-images.githubusercontent.com/110182832/205349495-c9f66651-7e2a-4892-b552-bbe5e2c354a9.png">

<img width="280" alt="linux_check_disc" src="https://user-images.githubusercontent.com/110182832/205349564-5f2b84c0-f2c8-4ae9-b2d6-28fad3ff5066.png">


## CRONJOB
- Cron is used to run scripts in background. At given time, it automatically runs the script and gives output to the given file path.

- Here, you need to give date and timing for the script to run
- To open cronfile run
- 'crontab -e'

- put * for the day and time you want to run the script, then give command that 
  you want to run
 - Here * * * * * means the script will run evry minute, evry hour, every day of every month and 'bash /home/ubuntu/scripts/check_disk.sh' is the command which we want to run
 - 'bash file_name'is used to run shell script
 - In above case bash and then path of the script file is given which is going to run
 
- '>>' will append that output into destination file which is /home/ubuntu/check_disk_logs.text
- It will create a check_disk_logs.txt file at /home/ubuntu location and give the output

![WhatsApp Image 2022-12-02 at 17 26 34](https://user-images.githubusercontent.com/110182832/205350585-f756be91-5b74-4151-aa12-1eaae0eaef2c.jpeg)

<img width="527" alt="cron job" src="https://user-images.githubusercontent.com/110182832/205349817-be81e0e1-fcda-4c4a-9298-65c08bcb265e.png">

Youtube video for: (In Hindi)
Scripts: https://www.youtube.com/watch?v=UYstAfqkLtg&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=4
CRONJOB: https://www.youtube.com/watch?v=aolKiws4Joc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=6
