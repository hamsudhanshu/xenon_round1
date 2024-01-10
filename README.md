Section A

Each linux command has an option --help which helps the end user to understand the use cases via examples. Similarly if I execute internsctl --help it should provide me the necessary help
Solution - To do this i have go to to root directory using below command


![Screenshot 2024-01-10 161326](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/598cb14f-cbbb-4c5a-a49d-baed6bd55e00)

used nano command to create custom command and write nano internsctl


![Screenshot 2024-01-10 161545](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/417cb39f-6748-4460-b58a-3139bb30f98c)


now the custom commands is created.

Output:-

![image](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/f006eaba-7496-4f42-ad9a-bca9878b6ca1)

I want to see version of my command by executing internsctl --version

Output-

![image](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/fb3d4964-fc1c-4609-aaf3-aaac12a7a5d0)


Section B I want to execute the following command for - Part1:- Level Easy I want to get cpu information of my server through the following command: $ internsctl cpu getinfo

Solution:-

Inside root write nano internsctl cpu getinfo and write lscpu in it

Output-


![image](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/d9168a11-709c-40c9-8b74-d7364f0077f8)

art2 | Level Intermediate I want to create a new user on my server through the following command:

I want to list all the regular users present on my server through the following command: $ internsctl user list
Solution-

Inside root write nano internsctl user list and write cat /etc/passwd in it

Output-


![image](https://github.com/hamsudhanshu/xenon_round1/assets/116375492/c28275cb-dd93-4c84-b009-15f68aa4a57d)
