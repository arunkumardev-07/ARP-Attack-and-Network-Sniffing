# ARP-Attack-and-Network-Sniffing

# Explore Network Sniffing and ARP Attacks

## AIM:

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
![image](https://github.com/SivaramakrishnanBaskar/ARP-Attack-and-Network-Sniffing/assets/119476322/93e3d23d-50e3-4400-9aab-51a656d60f4c)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/ARP-Attack-and-Network-Sniffing/assets/119476322/4d20702c-34d4-46cf-b093-6c82a51300ba)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/ARP-Attack-and-Network-Sniffing/assets/119476322/6ae8c93d-4b79-40ef-9b4a-596a47f25aaa)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/ARP-Attack-and-Network-Sniffing/assets/119476322/258e7cb1-b78a-4cbc-a27d-1aaf04ce470a)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/SivaramakrishnanBaskar/ARP-Attack-and-Network-Sniffing/assets/119476322/9b1c8c1b-4f36-4b02-8641-7e8ffd9affa1)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
