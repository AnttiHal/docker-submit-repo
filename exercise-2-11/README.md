I was starting a wordpress project for my client and for the first time I tried to use docker in local development process. Usually I have used MAMP.
I googled some instructions and I managed to get wordress with mysql and phpmyadmin up and running quite easily.
 I created .yml-file which gives instructions to set up wordpress, mysql and phpadmin.
I set up bind mounts for wordpress files and for database to point to same directory where yml-file is. 
I uploaded theme files and put them to binded local file and everything seems to be working.
Now I'm able to continue developing via browser or editing code via text editor. 
docker-compose.yml file included.

