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

![Screenshot 2024-09-24 200419](https://github.com/user-attachments/assets/6c66e554-3fa1-4ec0-9839-1dbff9255812)





## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping www.google.com
```
## Output:

![ping](https://github.com/user-attachments/assets/44a4882f-5bbe-49c9-8d51-5dc58a725b99)

## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:

![Screenshot from 2023-05-15 04-32-04](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/ad2a8edd-7197-44ae-9f54-94375c7114a9)


## History of the website:
## Output:
https://web.archive.org/


![Screenshot from 2023-05-15 04-42-06](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/192a1d85-246e-45ad-bcd0-0a70e209c601)




# Webserver Fingerprinting:

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![nmap](https://github.com/user-attachments/assets/59ffc8dd-f25f-41aa-a9ca-d973e73a5fb6)




## Whatweb:
```
whatweb bing.com
```
```
whatweb microsoft.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:

![whatweb](https://github.com/user-attachments/assets/c33f8b1f-5132-4424-866a-ef9a8bf5299a)

![318627802-94b2bd7c-ecf2-4421-8a53-10e1c056b1aa](https://github.com/user-attachments/assets/1415c967-bd2b-49c8-aada-e0ab3014922a)



## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![httprint](https://github.com/user-attachments/assets/7f378541-2fcd-4b8a-89a6-ad0b2ad5c4be)





# Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.youtube.com
```
## Output:


![tcp traceroute](https://github.com/user-attachments/assets/4532137e-726c-4246-aa22-4e775fb2f106)




## UDP Traceroute:
```
sudo traceroute -U www.chrome.com
```
## Output:


![udp traceroute](https://github.com/user-attachments/assets/f1663eb6-075e-43af-a487-2ae4246a7096)




## ICMP Traceroute:
```
sudo traceroute  www.bing.com
```
## Output:

![traceroute](https://github.com/user-attachments/assets/87591fac-9203-41aa-93ae-a1d6c3206b89)




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
