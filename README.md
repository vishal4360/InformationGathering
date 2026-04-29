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

<img width="631" height="86" alt="Screenshot From 2026-01-30 09-44-57" src="https://github.com/user-attachments/assets/2235fb00-1487-4d29-b0fb-b80fb532a4d1" />

## nmap:
## output

<img width="696" height="253" alt="Screenshot From 2026-01-30 09-45-07" src="https://github.com/user-attachments/assets/3aa121a9-8a5a-4dbc-bb4b-160a11ae396b" />

## Whatweb
### output

<img width="1914" height="208" alt="Screenshot From 2026-01-30 09-45-22" src="https://github.com/user-attachments/assets/6bb1731d-07d8-47e2-9b15-dc633fbb6c7b" />

## httprint
### output

<img width="752" height="920" alt="Screenshot From 2026-01-30 09-45-40" src="https://github.com/user-attachments/assets/bbcd77ef-ac9e-4000-8507-0134e9a15de9" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T instagram.com
## output

<img width="776" height="105" alt="Screenshot From 2026-01-30 09-45-59" src="https://github.com/user-attachments/assets/6c3218aa-f976-4b9f-af0b-de536c150154" />

## UDP Traceroute:
sudo traceroute -U instagram.com
## output

<img width="607" height="192" alt="Screenshot From 2026-01-30 09-46-13" src="https://github.com/user-attachments/assets/2e3111f9-5664-4863-bc79-8092aaf101e9" />

## ICMP Traceroute:
sudo traceroute instagram.com
## output

<img width="607" height="192" alt="Screenshot From 2026-01-30 09-46-20" src="https://github.com/user-attachments/assets/b647cd01-45a8-47cc-95b1-d3b387885ac3" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
