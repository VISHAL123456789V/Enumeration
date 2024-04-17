# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
## Name: Vishal T
## Roll.no: 212223100060
## Dept: CSE(Cys)
## AIM:

To use Google for gathering information and perform enumeration of targets

### STEPS:

#### Step 1:

Install kali linux either in partition or virtual box or in live mode

#### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


#### Step 3:
Open terminal and try execute some kali linux commands

### Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain youtube.com


![1](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/9236f097-0c2a-4c4c-97f2-110db0a71d26)




#### filetype: 

![2](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/6a5a1a35-c421-4003-8ea3-17a6ccccc79a)

This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

#### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![3](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/08b94f42-454e-4b6a-8019-a3c70a4ae1bd)


#### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![4](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/b606a0ea-ee38-4c33-95c2-b6f9056e48cf)


#### intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![5](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/70474ca5-2320-4418-bba9-1415e1e317b2)




#### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![6](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/ce0aef36-36a2-4f95-927e-c82a743c5188)

#### cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![7](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/fae40b6f-f312-429e-8dac-7c241c3e962f)


 
### DNS Enumeration


#### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
#### OUTPUT:
![8](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/36e932f6-97b9-422c-a2f3-84657b63ece2)


#### dnsenum
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
![9](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/9911c81a-f4fb-463a-a124-954689963b95)



#### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
![10](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/a1c5e0c4-312d-45e9-8ba1-5e08940b1ed1)


select any username in the first column of the above file and check the same
![11](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/25b35b31-0069-4481-a526-d9e46533de5a)



#### Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
#### Output
![12](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/4007c417-e69e-4785-bb50-9de1cd6910f3)

  

#### nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


#### OUTPUT:
![13](https://github.com/VISHAL123456789V/Enumeration/assets/161364099/c2bde798-e5d2-40c9-86ab-0be3bab79e99)

 
 

### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

