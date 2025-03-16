# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```PYTHON
Developed by   :  SANJAY M
Register no    :  212223230187
```
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

## Google Hacking:

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

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## dnsenum
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


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
  
# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

## OUTPUT:
## site:
![Screenshot 2025-03-15 131844](https://github.com/user-attachments/assets/a4ab2dbf-59b6-45f9-9c92-79042c2bb20b)


## filetype:
![image](https://github.com/user-attachments/assets/e17769c3-2c0d-46f8-8f82-ccfc8df25053)


## intext:
![image](https://github.com/user-attachments/assets/509cf47e-633f-4b3a-a71f-57be88c4bdef)


## inurl:

![image](https://github.com/user-attachments/assets/31bb1d3b-ca87-4ada-816e-09968dbb4c1e)


## intitle:
![image](https://github.com/user-attachments/assets/14577a7f-42eb-4472-96bb-ba394e86d6d0)


## link:
![image](https://github.com/user-attachments/assets/e6a79e91-0bbb-400e-94f2-b1542889cadd)


## cache:

![image](https://github.com/user-attachments/assets/091308e1-ea6a-405c-90c3-86e44638248c)


## DNS Enumeration:
## DNS Recon:
![image](https://github.com/user-attachments/assets/0296dcaa-cf28-45be-9943-6895d2fe96bd)




## dnsenum:
![image](https://github.com/user-attachments/assets/5039cb66-a4c8-4c1c-9753-8bf17200e86c)
![image](https://github.com/user-attachments/assets/9688a205-df95-4b13-a6f3-e03d6113d8fc)
![image](https://github.com/user-attachments/assets/427d9cb9-7309-4b93-b0f3-0310ddbe22d7)
![image](https://github.com/user-attachments/assets/cf5423b9-5de2-41e5-8420-a70a89f492f9)


## smtp-user-enum:

![image](https://github.com/user-attachments/assets/3562608e-f08d-42b6-b454-4a51d4e053b7)
![image](https://github.com/user-attachments/assets/7662583c-a5ba-406b-a77e-629dcbd2299d)


## telnet:
![image](https://github.com/user-attachments/assets/9eb401ff-a072-4591-8787-fc4d3efee58e)
![image](https://github.com/user-attachments/assets/1ab11e32-ea68-47cd-91b3-8683f14409e5)
![image](https://github.com/user-attachments/assets/8d8a6908-93cf-4bb6-a322-c402a2d00daf)


## nmap –script smtp-enum-users.nse :

![image](https://github.com/user-attachments/assets/89ad6477-6d21-4b28-971f-e84b1655bc5f)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


