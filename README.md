# Information Gathering
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

<img width="1919" height="1069" alt="image" src="https://github.com/user-attachments/assets/8c1778ea-87ec-4023-a71d-60b89faad478" />

<img width="1917" height="1066" alt="image" src="https://github.com/user-attachments/assets/88f223ff-3e94-4a67-b54d-bf6be560fad4" />

<img width="1913" height="1067" alt="image" src="https://github.com/user-attachments/assets/6f495dd6-cd16-4b20-b77b-d511dd669e8d" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output



## Finding Hosting Company
get further detail by using ip2location.com website.

## output

<img width="1910" height="1055" alt="image" src="https://github.com/user-attachments/assets/8449b671-5973-420e-afd9-524e82bf0446" />

<img width="1916" height="1062" alt="image" src="https://github.com/user-attachments/assets/3f2744e5-c677-4f48-89d5-7c8805854b3c" />


## History of the website:

https://web.archive.org/

## output

<img width="1239" height="737" alt="image" src="https://github.com/user-attachments/assets/9d103386-71ea-4de3-8363-3646414b33cc" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com




## nmap:

### output

<img width="945" height="262" alt="image" src="https://github.com/user-attachments/assets/8cb5cfbb-8db3-4d73-88ea-5fe1da74656d" />


## Whatweb
### output

<img width="1908" height="1119" alt="image" src="https://github.com/user-attachments/assets/d86b9f7e-471c-467c-a040-7d71a3432760" />


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

<img width="962" height="437" alt="image" src="https://github.com/user-attachments/assets/d90bae9a-8aa3-419b-b5d0-fa53f1cc8983" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="956" height="546" alt="image" src="https://github.com/user-attachments/assets/c915df25-90b3-4553-8075-eacf0f3e21ea" />




## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="753" height="93" alt="image" src="https://github.com/user-attachments/assets/eb38cc7a-4fc3-4746-af57-d9f112a0fd30" />





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
