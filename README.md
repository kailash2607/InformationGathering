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

![WhatsApp Image 2025-03-08 at 14 16 11_f5aabc22](https://github.com/user-attachments/assets/39ae4838-320f-4b34-b90c-e63a072cfd5e)

![WhatsApp Image 2025-03-08 at 14 16 10_2d45f5f2](https://github.com/user-attachments/assets/8b3c80af-db37-4f28-a6ce-b92666cbc4ea)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping rockstargames.in
```
## Output:

![Screenshot 2025-03-08 144458](https://github.com/user-attachments/assets/1834974e-c2bb-4a48-84d2-8f1b51adfcc3)

## Finding Hosting Company
get further detail by using ip2location.com website.

## Output:

![WhatsApp Image 2025-03-08 at 14 16 11_8ce7458b](https://github.com/user-attachments/assets/1fb28adf-6d2d-4e64-bf24-05d9f9843b08)

## History of the website:
## Output:

![WhatsApp Image 2025-03-08 at 14 16 11_6c12059a](https://github.com/user-attachments/assets/fb7369f2-97b9-45fd-88d3-4c74d78ee775)

## Webserver Fingerprinting:
## Netcat:
```
nc rockstargames.com 80
```
## Output:

![Screenshot_2025-03-08_04_16_19](https://github.com/user-attachments/assets/712fab1c-e2fd-4e61-b81d-b11985425d58)

## nmap:
```
nmap rockstargames.com
```
## Output:

![Screenshot_2025-03-08_04_18_56](https://github.com/user-attachments/assets/7dc69480-a232-4828-b058-00a85fed3374)

## Whatweb:
```
whatweb rocktargames.com
```
## Output:

![Screenshot_2025-03-08_04_20_18](https://github.com/user-attachments/assets/8546ba0d-cce0-4d68-9674-1288db255b69)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:


## Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T rockstargames.com
```
## Output:

![Screenshot_2025-03-09_23_57_21](https://github.com/user-attachments/assets/a27da9cd-279e-46c8-ad44-171a990e1daa)

## UDP Traceroute:
```
sudo traceroute -U rockstargames.com
```
## Output:

![Screenshot_2025-03-08_04_24_09](https://github.com/user-attachments/assets/d91a7e7e-8779-44b4-82de-1fd4d8a39a16)

## ICMP Traceroute:
```
sudo traceroute  rockstargames.com
```
## Output:

![Screenshot_2025-03-08_04_22_44](https://github.com/user-attachments/assets/ff2051cb-fada-4e81-af0f-041d7d7e7706)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
