# **Intermediate Namp**

Challenge Link: https://tryhackme.com/room/intermediatenmap

## **Objectives:**

In this Room, we have to log in th machine and catch the flag into the machine by using the Nmap Tool.
So, now let go to the Process

## **Step 1:**

 First, we have to scan the Machine via nmap to find the services on running ports. 
<br>

```
sudo nmap -sC -sV <machine_ip>
```

![Scanning the Target](https://github.com/DawoodRomeo/TryHackMeCTF/blob/main/src/Intermediate%20Nmap/nmap_scan.png)

after the scanning we can see the creddiential under the *user:pass* for log into the target machine via ssh protocol.
so, in the next step we have to access the machine via ssh.

## **Step 2:**

Access the machine via ssh by using the above crediential
<br>

![ssh Login](https://github.com/DawoodRomeo/TryHackMeCTF/blob/main/src/Intermediate%20Nmap/ssh_login.png)

we successfully gain the access of machine. now, we have to find the .txt file which contain the flag.

## **Step 3:**

we find the flag.txt file in the "user" directory.
<br>

![Alt text](https://github.com/DawoodRomeo/TryHackMeCTF/blob/main/src/Intermediate%20Nmap/flag.png)
Congtratulations , we captured the flag. 
