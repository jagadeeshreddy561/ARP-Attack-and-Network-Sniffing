
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:



![EHT-EXP-3 1](https://github.com/jagadeeshreddy561/ARP-Attack-and-Network-Sniffing/assets/120623104/9517393f-5ddb-43a4-8d88-99614a64e8d4)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:




![EXP-3 2](https://github.com/jagadeeshreddy561/ARP-Attack-and-Network-Sniffing/assets/120623104/9c1cad63-dcba-430c-bfc8-60889c71a0f7)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![EXP-3 3](https://github.com/jagadeeshreddy561/ARP-Attack-and-Network-Sniffing/assets/120623104/e7f74755-a5fd-4e47-a516-f7007ed8e822)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![EXP-3 4](https://github.com/jagadeeshreddy561/ARP-Attack-and-Network-Sniffing/assets/120623104/48c17339-9f7f-41f2-9caa-afe05b3183e0)


Invoke the wireshark and examine the various menus  and controls of the tool:

![EXP-3 5](https://github.com/jagadeeshreddy561/ARP-Attack-and-Network-Sniffing/assets/120623104/19672d86-29e2-4410-b558-187df4636dd2)








## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
