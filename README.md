# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

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


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="1896" height="1029" alt="image" src="https://github.com/user-attachments/assets/a9fa21e7-762d-4090-9af3-ffb5e3bfc078" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1884" height="1018" alt="image" src="https://github.com/user-attachments/assets/0f7869a8-086a-4535-a4f8-12731b4504a0" />


## History of the website:
## output
https://web.archive.org/

<img width="1896" height="945" alt="image" src="https://github.com/user-attachments/assets/16af4ff9-cfd1-42e8-a252-0e91b3a4444e" />

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="1920" height="1080" alt="netcat" src="https://github.com/user-attachments/assets/cb0a6c9b-d219-4f83-9637-743fd4d6c5e5" />


## nmap:
###output
<img width="1920" height="1080" alt="nmap" src="https://github.com/user-attachments/assets/9578d49c-f31d-48e7-a7b3-d1fc92a56752" />


## Whatweb
### output
<img width="1920" height="1080" alt="whatweb" src="https://github.com/user-attachments/assets/dbcc2fed-6200-4a23-a128-48ce0ddd0929" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.flipkart.com
## output
<img width="1920" height="1080" alt="-T" src="https://github.com/user-attachments/assets/3e523042-36d5-4a9c-bd6b-273444789f40" />


## UDP Traceroute:
sudo traceroute -U www.flipkart.com
## output

<img width="1920" height="1080" alt="-U" src="https://github.com/user-attachments/assets/9b646645-1427-4856-ab74-1d5196d9be01" />


## ICMP Traceroute:
sudo traceroute  www.flipkart.com
## output

<img width="1920" height="1080" alt="111" src="https://github.com/user-attachments/assets/19b3d96e-3d2f-4275-8e6b-6dff3119147e" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
