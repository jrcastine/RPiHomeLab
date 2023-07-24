Files relating to my Raspberry Pi "Home Lab".

For reference, this is a Raspberry Pi 4B 4 GB model, running Raspberry Pi OS 64 bit lite version and OpenMediaVault 6.  There is a 500 GB external NVMe drive connected and shared for NAS storage.

These are the .yml files that I am using in my instance of Portainer. Some items to note prior to use.

* These .yml files are for use in creating an application stack in Portainer.
* You will need to update the volumes tags on these .yml files prior to use.
* You will need to update the PUID and PGID environment varialbles for you Portainer instance.

Each container is accessible as shown below.  You can of course edit the .yml files to use ports on your Portainer host as you see fit. I do recommend leaving the ports for the OWASP Juice Shop as they are currently set to ensure that application operates normally.

* Cyberchef will be accessible at http://YOUR_IP_ADDRESS:85
* FreshRSS will be accessible at http://YOUR_IP_ADDRESS:8181
* OWASP Juice Shop will be accessible at http://YOUR_IP_ADDRESS:3000
* DVWA will be accessible at http://YOUR_IP_ADDERESS:4000
* podgrab will be accessible at http://YOU_IR_ADDRESS:8282
