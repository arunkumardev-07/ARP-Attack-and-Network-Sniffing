# ARP-Attack-and-Network-Sniffing
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
![270711185-af970103-9fb9-429d-acf8-1f5d094219ca](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/9cef5065-4b18-41f5-a979-fcbf0fd66a2c)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![270708637-c994f650-351b-421d-aa03-2e5eff65d613](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/2f669647-55d0-4f2a-8048-5e6337faeb9b)

 
 # dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![270708637-c994f650-351b-421d-aa03-2e5eff65d613](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/4d7e7751-5aa7-4259-8512-ca0859710a90)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![270708938-c6850bfd-dd4a-42f7-83cf-0c48ddb49067](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/88dd005a-8c0f-4f94-b899-ebf4dee1a8a2)


## WIRESHARK
Invoke the wireshark and examine the various menus  and controls of the tool:
![270709207-53d046a7-f3d4-44db-b00c-4757086bb690](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/81caee02-ba87-4ad3-8582-cfa2913d3f34)

## ETTERCAP
![270709799-88e2faef-2c64-410b-bcce-0072e4d0f85f](https://github.com/Sanjay-2610/ARP-Attack-and-Network-Sniffing/assets/91368803/95ce6bce-745c-4835-9137-6db366225214)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
