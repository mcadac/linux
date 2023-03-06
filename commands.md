# Commands

1. Show what process is running on a specific port.

    **sudo netstat -lnpt | grep "puerto**
    
2. Show what is the service's port.

    **ps aux | grep "servicio"**
    
    **sudo netstat -lnpt | grep "proceso"**

3. Show memory use

   **sudo df -h**
   
4. Create a ssh connection
   
   **ssh username@ip-server** 

6. Go home trick

   **cd + two spaces**
   
7. Create a file 

   **touch filename.txt**
   
   Create a file in the future
   
   **touch -d tomorrow filename.txt** 
   
8. Write an echo or result in a file

   **echo "test this" > filename.txt**
   
9. Remove directory

   **rmdir directory-name**
   **rm -r directory/**
   
10. See which user I am

   **whoami**
   
11. Add user

   **sudo useradd newuser**
   **sudo adduser newuser**
   
12. Change user 

   **su nameuser**
   
13. Chane passwors

   **sudo passwd username**
   
14. Show where a command is set up

   **whereis java**
   
15. Zip and Unzip a file

   **zip filename.txt**
   **unzip filename.txt**
   
16. Read a file from terminal  (better than cat)

   **less filename.txt**
   **head filename.txt**
   **tail filename.txt**
   
17. Compare files 

   **cmp filename1 filename2**
   
18. Show difference between files

   **diff filename1 filename2**
   
19. Sort command

   **ls | sort**
   **cat filename.txt | sort**
   
19. Find a file 

   **sudo find / -name "filename"**
   **sudo find . -type f -name ".*"**
   **find . -type f -empty** this is to find empty files

20.  Make a file executable

   **chmod +x executablefile.sh**
   
21. Change owner on the file 

   **chown username file**
   
22. Greap command

   **ifconfig | grep utun0**
   **ifconfig | grep utun0 | awk '{print $2}'**

23. ping command

   **ping -c www.google.com**
   
24. if we want to see the request's route

   **traceroute www.google.com**
   
25. Know more about our system

   **uname -a**
   
26. Print out a calendar

   **cal**

27. Make math calculation from terminal

   **echo "2+3+4+5" | bc**
   
28. How much space do we have

   **df**
   **df -h**
   **top**
   **htop**
   


 
