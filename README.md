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


## OUTPUT:
# www.whois.com:
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/a111dcb9-790f-4fc3-acd2-328abb4007f5)
# Finding IP address:
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/40d8d2e0-272e-489f-ba7f-e9e6a3520b8b)
# Finding Hosting Company using ip2location:
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/71e252a9-5e91-4b59-b007-d95e454c34e6)
# HISTORY OF WEBSITE:
```
https://web.archive.org/
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/95e91407-bf64-4e59-8d76-51cf1c3ac0f7)
# Webserver Fingerprinting:
# Netcat:
```
nc 172.17.52.118 80
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/1c658e73-18e8-407d-8bec-871082a27e09)
# nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/7a480c06-758b-49b7-9033-9902cf0929b2)
# WHATWEB:
```
whatweb zoho.com
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/4434e05c-444f-4659-9ef1-8145d5293d95)
# httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/838cccc9-590d-49d9-86b5-7efdd81c84dc)
# Tracing the Location
TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/b8926732-0e41-4407-bb80-38f42c02c3cf)
# UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/89a1cbfa-b253-4045-b9e0-f38e8b7004a2)
# ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/SVENGADAKRISHNAN/InformationGathering/assets/147473084/b6057fb9-8ceb-485f-b6fc-3f5737374a2f)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
