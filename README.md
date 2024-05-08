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
![image](https://github.com/Vanitha-SM/ARP-Attack-and-Network-Sniffing/assets/119557985/4aaa3760-fa61-47f0-b5d8-a27e189ba522)




From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

![image](https://github.com/Vanitha-SM/ARP-Attack-and-Network-Sniffing/assets/119557985/4a43f3dc-5a5e-430c-9bd5-8eb7e40aad38)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Vanitha-SM/ARP-Attack-and-Network-Sniffing/assets/119557985/155d5091-7cf6-4021-a380-109b48220adc)


In Kali issue the following commands:
sudo dsniff
## OUTPUT:

![image](https://github.com/Vanitha-SM/ARP-Attack-and-Network-Sniffing/assets/119557985/7746b708-d0a9-452a-b511-e52e88a31bd4)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Vanitha-SM/ARP-Attack-and-Network-Sniffing/assets/119557985/8b74b83c-6ac7-475c-9182-b189f3ce1c0f)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
