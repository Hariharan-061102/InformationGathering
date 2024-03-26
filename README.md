# To perform information gathering techniques

## AIM:

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
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/84ee3840-46d4-4b69-ad21-954f46308e81)


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping google.com
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/2dc7990f-2aaf-4067-8104-c7f119b35db4)



## Finding Hosting Company
```
get further detail by using ip2location.com website.
```

## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/0fc6023a-0663-4db9-93e1-c6c90ebe3454)



## History of the website:
## Output:
https://web.archive.org/
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/45987ba0-02f2-49ac-9602-d17c8958fb8e)


## Webserver Fingerprinting:
### Netcat:
```
nc 172.17.52.118 80
```
## Output:

![]()

## nmap:
```
nmap -vvv -sV 192.168.23.133
```
## Output:
![Screenshot 2024-03-22 110607](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/7ca989dc-402d-4e4b-8112-61de863c3b28)



### Whatweb:
```
whatweb google.com
```
```
whatweb yahoo.com
```
```
whatweb -v -a 3 172.217.160.174
```
### Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/31726de4-547e-4cf9-92ba-5f1e7e5f4bc9)

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/e1eefe87-7eff-474d-969e-38cda47ed8ea)

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/6ce7eb16-8ceb-42d4-b655-61791bc3b6f9)



## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:

![]()

## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T www.google.com
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/00668b61-a98c-41af-95ea-0b17df5697c5)



## UDP Traceroute:
```
sudo traceroute -U www.google.com
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/5fa5ecc3-1f19-497d-872f-30b809e188c3)



## ICMP Traceroute:
```
sudo traceroute  www.google.com
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/f6e32235-ed28-4658-9028-4ed467cd266c)

## RESULT:
The information gathering techniques tools/procedure were identified successfully
