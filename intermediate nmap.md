# **Intermediate Namp**

## **Objectives:**

### In this Room, we have to log in th machine and catch the flag into the machine by using the Nmap Tool.

### So, now let go to the Process

## **Step 1:**

### First, we have to scan the Machine via nmap to find the services on running ports. 
<br>

```
sudo nmap -sC -sV <machine_ip>
```

![Scanning the Target](nmap_scan.png)

### after the scanning we can see the crediential for log into the target machine via ssh protocol.

```
user:pass
ubuntu: Dafdas!!/str0ng
```

### so, in the next step we have to access the machine via ssh.

## **Step 2:**

### Access the machine via ssh by using the above crediential
<br>

![ssh Login](ssh_login.png)

### we successfully gain the access of machine. now, we have to find the .txt file which contain the flag.

## **Step 3:**

### we find the flag.txt file in the "user" directory.
<br>

![Alt text](flag.png)

### Congtratulations , we capture the flag and we solved this room. 