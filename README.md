# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques
# Name : VISHAL.C
# Register No : 212224100062
# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1919" height="1149" alt="Screenshot 2026-01-30 092508" src="https://github.com/user-attachments/assets/23d9b6ac-b2bb-4270-99f4-1a82dee7695f" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="745" height="301" alt="image" src="https://github.com/user-attachments/assets/7501956e-c70b-45d7-9554-90e5a64fcea5" />


## Finding Hosting Company
get further detail by using ip2location.com website.
# output

<img width="1918" height="1151" alt="image" src="https://github.com/user-attachments/assets/c157c462-40aa-4d83-922c-063d3288a64c" />

## History of the website:
## output
https://web.archive.org/

<img width="1919" height="1150" alt="Screenshot 2026-01-30 095154" src="https://github.com/user-attachments/assets/00262445-2f6c-4e0f-9fdd-f535f300f4f0" />


# Webserver Fingerprinting:

## Netcat:
sudo nc instagram.com 443
GET / HTTP/1.1
Host: instagram.com

<img width="688" height="156" alt="nc -z" src="https://github.com/user-attachments/assets/8a494edd-5f0e-4a5c-982a-ea115c94c825" />



## nmap:
## output

<img width="757" height="448" alt="nmao" src="https://github.com/user-attachments/assets/42bbdbba-e86a-4c74-ac5e-dc69df9d47c6" />

## Whatweb
### output

<img width="1138" height="733" alt="what web" src="https://github.com/user-attachments/assets/dcb32109-b115-4982-a0bf-6b1c61fc249d" />

## httprint
### output

<img width="1263" height="829" alt="http" src="https://github.com/user-attachments/assets/460bab09-f1ad-44b5-b165-8fb06e8498be" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T instagram.com
## output

<img width="800" height="184" alt="-t" src="https://github.com/user-attachments/assets/53757dd4-a839-4087-b01f-17dfa660b01f" />


## UDP Traceroute:
sudo traceroute -U instagram.com
## output
<img width="777" height="487" alt="u" src="https://github.com/user-attachments/assets/685964f6-dea6-4ba3-bec6-206b5fc75b20" />


## ICMP Traceroute:
sudo traceroute instagram.com
## output

<img width="750" height="373" alt="Screenshot 2026-05-01 145930" src="https://github.com/user-attachments/assets/65b03458-c5d3-4b50-9a21-8d8034349118" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
