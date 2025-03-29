# CCNP-LABs
Courses for the CCNP ENCOR 350-401 exam 
![image](https://github.com/user-attachments/assets/a05fe659-4860-4c92-9e95-6494b194e35f)
ASW-1#sh
ASW-1#show run
ASW-1#show running-config 
Building configuration...

Current configuration : 1397 bytes
!
! Last configuration change at 17:04:41 UTC Sat Mar 29 2025
!
version 15.2
service timestamps debug datetime msec
service timestamps log datetime msec
no service password-encryption
service compress-config
hostname ASW-1    
      
interface Ethernet0/0
 switchport access vlan 10
 switchport mode access
!        
interface Ethernet0/1
!         
interface Ethernet0/2
 switchport access vlan 20
 switchport mode access
     
end       
