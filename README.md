# Lab 02
## 1
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/1.png)

## 2
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/2-1.png)
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/2-2.png)

## 3
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/3.png)

## 4
Setting umask to 0027 will mask the write permissions of the group and all permissions of other users. Thus the permissions of any file created will have -rw-r----- by default.
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/4.png)

## 5
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/5.png)

## 6
Copying failed when user1 tries to copy progit.pdf from /home/project to /home/user1. As per my observation even though the user1 is a part of the group project1 and the group having permissions to project1/ directory. As the owner of the directory is seed, the file downloaded has got the default owner and group as seed instead of having the group project1. This made the user1 ineligible to copy the file to /home/user1
![](https://raw.githubusercontent.com/sri-nivas1227/Computer-Security-Coursework/main/6.png)
