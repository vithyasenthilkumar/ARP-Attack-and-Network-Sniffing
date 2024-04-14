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
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
![image](https://github.com/vithyasenthilkumar/ARP-Attack-and-Network-Sniffing/assets/127177445/2b189817-c9be-4b2f-a4a8-fc1aa6531e11)
From Kali linux issue the command : sudo arpspoof -i etho -t
![image](https://github.com/vithyasenthilkumar/ARP-Attack-and-Network-Sniffing/assets/127177445/6aac1a9e-b424-4c28-a24e-3810e17eb68c)
 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/vithyasenthilkumar/ARP-Attack-and-Network-Sniffing/assets/127177445/f680d9a7-3814-4d78-8bde-cc1afb743cd4)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/vithyasenthilkumar/ARP-Attack-and-Network-Sniffing/assets/127177445/510f0e9f-01f6-49e9-a133-6a6296139154)
Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/vithyasenthilkumar/ARP-Attack-and-Network-Sniffing/assets/127177445/19c33e91-31d9-49f7-b0ba-542c7c26ee70)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
