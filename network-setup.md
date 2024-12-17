1941 Router0

2960-24TT Switch0
PC0 IP: 168.90.0.11
PC1 IP: 168.90.0.12
Laptop0 IP: 168.90.0.13
Server0 IP: 168.90.0.14

2960-24TT Switch1
Server1 IP: 210.3.14.11
Server2 IP: 210.3.14.12
PC2 IP: 210.3.14.13

Updates:  
On Switch0 - PC3 
On Switch1 - PC4

New Branch updates:  
I entered into CLI of the router and accessed both of the interfaces (GigabitEthernet0/0 and 0/1)  
added them given ip addresses and dns (ip address x.x.x.x 255.255.x.x) also I used no shutdown command  
After that I made two pools for two of my switches (ip dhcp POOL_NAME), and than used commands (networ and default-router)  
to assign default ip addresses. Than I excluded two addresses which will be assigned to the routers.  
Then I went to every end device, desktop tab, Ip config and switched to DHCP. Every end device got its automatic  
ip address 

