# iot_entanglement
Security app

This repository will contain a suite of security tools
for the purpose of iot remote monitoring.
   
The structure includes a web server, security server, network of devices, and 
 an internet connection. Also a cell phone with network access, and remote web access.

   
The phone will acess the security server on the network. The sever will issue the phone
with a set of encryption keys, block chains, etc.
   
The phone will then disconnect from the network and can be carried to a remote
location with internet access. The phone can then access a web server that 
has a communication link to the security network. The phones
encrption can then pass through the internet to the security netwrok
and visa versa. The web host - i.e. AWS, will not be
able to trivially decode the shared information.

### Project plan.   
   
-the bulk of the project can be built in php.
-the main issue is the mobile apps real security and privact.
- the mobile app may have to be a web app which also suffers from security issues
- post messages may be less secure than a tcp/ip link for exanple.
