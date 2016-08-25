# core
The Core of The DIREKTSPEED - Application Delivery Controller

Loadbalancing
Firewall
Modification Proxy
User Authencication Managment
Monitoring

The Core is able to Fetch The Installed modules and Configurate them Via Api

dsadc is simply a command line client for this api
dsadc can connect to this via ssh + socketfile or directly to this socketfile or via remote address port exposed api if installed dsadc-core-http
if you install that on the core machine then it will automaticly use it to offer http services on port 6082
via credentials supplyed in ENV Vars of this core machine

You can Encrypt the Real config that is stored in the env var with sha1 and use the machine ID that the core creates as password.

as the machineid creation process is costumise abled sha1 hash you can 
