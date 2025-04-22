# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:







##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

## site:example.com
![L-3 IMG 1](https://github.com/user-attachments/assets/f4a99021-ae78-4296-83eb-ff49575f96c1)


## filetype:pdf
![L-3 IMG 2](https://github.com/user-attachments/assets/3f9d3532-f070-4f93-9037-6e909bc7cc53)


## intext:password
![L-3 IMG 3](https://github.com/user-attachments/assets/5f26a1fb-1df1-440e-8d14-c928acfc1ada)


## inurl:admin
![L-3 IMG 4](https://github.com/user-attachments/assets/9cffb0f7-766e-4dab-a181-200474ebb8ad)


## intitle:index of
![L-3 IMG 5](https://github.com/user-attachments/assets/99da960a-563d-4770-bc18-bc4762e2e1de)


## link:example.com
![L-3 IMG 6](https://github.com/user-attachments/assets/b9dcc481-35c4-4113-ab4b-64db7b84e780)


## cache:example.com
![L-3 IMG 7](https://github.com/user-attachments/assets/e4d61750-1b1e-4994-942e-dcd78251d64e)



## DNS Enumeration

## DNS Recon

![L-3 C1](https://github.com/user-attachments/assets/d3056223-f673-4d5b-904e-232410e5a45f)


## dnsenum
![L-3 C2](https://github.com/user-attachments/assets/1ed3d864-7d77-4264-a3be-a6d23d96ae31)


## smtp-user-enum
![L-3 C4](https://github.com/user-attachments/assets/e898c1f6-7f58-4ab4-9071-0cc938447738)


![L-3 C5](https://github.com/user-attachments/assets/7e32aaf7-3c0e-4162-be36-7abb91ac7800)



## Telnet for smtp enumeration
![L-3 C3](https://github.com/user-attachments/assets/8c5fade9-a15a-4089-b6e2-f93870b09c05)


## nmap-script smtp-enum-user.nse<hostname>
![L-3 C6](https://github.com/user-attachments/assets/176c896a-b392-4aa7-bf60-7c239eedb978)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

