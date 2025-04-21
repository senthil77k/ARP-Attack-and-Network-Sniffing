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
![Screenshot 2025-03-21 133647](https://github.com/user-attachments/assets/da64007c-3fb6-482d-8378-2b3510e7cab8)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-04-07 095823](https://github.com/user-attachments/assets/8792d6a6-83f5-49d5-9916-998f3abe4e5c)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2025-04-06 185724](https://github.com/user-attachments/assets/28a7319b-b534-464d-ae72-9aa0a91482ab)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/847ad8f6-4761-4b15-996c-8839298ee326)




Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![Screenshot 2025-04-06 193344](https://github.com/user-attachments/assets/c0876dfc-3671-40cb-8954-5bb0a86cecf7)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
