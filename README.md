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
#  OUTPUT:

![Screenshot 2025-03-15 075748](https://github.com/user-attachments/assets/d8e8e8bc-2aaa-4b56-858b-f432d72dd5f8)


![Screenshot 2025-03-15 080616](https://github.com/user-attachments/assets/9355d44a-591c-49ff-9a92-4894e90ed186)


![Screenshot 2025-03-15 080928](https://github.com/user-attachments/assets/5b14d262-6341-4c32-92c5-7df8a81db205)


![Screenshot 2025-03-15 081041](https://github.com/user-attachments/assets/9fbf757e-fcab-4087-84d2-20d6a67ae801)


![Screenshot 2025-03-15 081610](https://github.com/user-attachments/assets/18dd10de-d16d-46e2-afc9-39f9ca67490c)


![Screenshot 2025-03-15 081839](https://github.com/user-attachments/assets/6f69117d-2bf7-470d-9d01-5f1e638d4e05)


![Screenshot 2025-03-15 082711](https://github.com/user-attachments/assets/118237d0-f45d-4a19-818b-85913d8e4d9f)


![Screenshot 2025-03-15 083159](https://github.com/user-attachments/assets/14992008-b381-4988-af18-220f473767d5)


![smtp-user-enum](https://github.com/user-attachments/assets/8d1c0edf-5c9e-412c-83dc-7fb9e261b2a6)


![dnsenum](https://github.com/user-attachments/assets/43d22372-83eb-4c60-b998-c443aff97428)


![dnsrecon -d](https://github.com/user-attachments/assets/be341bf6-d687-412b-b9d0-944119f91853)



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
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

