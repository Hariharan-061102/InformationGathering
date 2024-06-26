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
ncat -C google.com
GET /HTTP/1.0

```
## Output:

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/c80acbc3-a197-48b5-8ddc-d61d0d4e47b9)


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
httprint -h 162.159.153.4 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:

![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/6856bf1e-3c62-4cd2-8469-e7b523dada37)


## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/d2a93aa7-3935-4174-a7f9-37bba41a7a0d)




## UDP Traceroute:
```
sudo traceroute -U lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/a91954da-205f-424e-ba97-ba83503d48f1)




## ICMP Traceroute:
```
sudo traceroute  lms.ai.saveetha.in
```
## Output:
![image](https://github.com/Hariharan-061102/InformationGathering/assets/93427270/775a3e19-9691-44de-942f-1b293b237418)


## RESULT:
The information gathering techniques tools/procedure were identified successfully
