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

### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

### DETAILED INFO:
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/8708b21c-8248-462b-b952-46c4c85424c3)

## Finding IP address:
ping facebook.com.

## OUTPUT:
![WhatsApp Image 2023-11-05 at 15 11 10_13176d54](https://github.com/KothaiKumar/InformationGathering/assets/121215739/6c5fe846-2bd9-4a91-b66a-7e188d596af9)

## Finding Hosting Company
ip2location.com website.

## OUTPUT:
![lab2(2)](https://github.com/KothaiKumar/InformationGathering/assets/121215739/8b1f113a-2e5f-4eef-84d2-2a47b17c96ad)

## HISTORY OF WEBSITE:
## OUTPUT:
![lab2(3)](https://github.com/KothaiKumar/InformationGathering/assets/121215739/6c59d26d-8b8f-4fe3-9f49-0f1c1c3dddb6)

## Webserver Fingerprinting:
Netcat:
sudo nc example.com 80 GET / HTTP/1.1 Host: example.com
## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/e76e2427-74fe-4a76-8296-2f3914aee557)

## nmap
## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/a88b0f50-38fd-46f0-85c9-35b29cb95ba2)

## whatweb
## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/1321070d-c415-4d8f-930a-f3d38128c6c8)

## Httprint
## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/3a3a1132-9e32-4507-864c-9d8b9cc2963b)

## Tracing the location
TCP Traceroute- sudo traceroute -T www.google.com
## OUTPUT:
![image](https://github.com/KothaiKumar/InformationGathering/assets/121215739/b83bb602-11a2-49a2-a5e6-6a68eab22d1b)

UDP Traceroute:
sudo traceroute -U www.google.com

## OUTPUT:
![WhatsApp Image 2023-11-05 at 15 21 31_f57515ae](https://github.com/KothaiKumar/InformationGathering/assets/121215739/22be84fd-8e27-41c0-89f7-055f764ef2fd)

ICMP Traceroute:
sudo traceroute  www.google.com

## OUTPUT:
![WhatsApp Image 2023-11-05 at 15 23 03_9bb08d1a](https://github.com/KothaiKumar/InformationGathering/assets/121215739/2fd776f7-406b-4794-9fcc-0316e5f991d4)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
