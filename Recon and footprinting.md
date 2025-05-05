
Footprinting and Recon or reconnaissance is an step in the cyber kill chain where you obtain information bout the target through all the sources you can find like their network structure,security protocols used etc… 



It will include both publicly available information (socials,google,etc..)and logical info (network scans and other advanced tools)


Stuff you need to figure out 
![[Pasted image 20241222145639.png]]

And it’s always recommended to use an report gathering template to record the data you find during the investigation (recon and footprinting)

## Competitive intelligence 

Competitive intelligence is an method of gathering information basically using all legal resources to find info bout the target you want to know about 
1. Job postings
2. Social media 
3. Google dorking 
4. News reports

Websites to use for competitive intelligence :
Linkedin
DICE
careerbuilder 
Monster 

Looking into code repos like GitHub,bitbucket and apache subversion

You can use public searchable databases for an companies information or per pay websites 
Some examples are
1. EDGAR (FREE) this contains documents from companies and other legal stuff you 
2. Google Finance 
3. Wikipedia 
4. Google Earth 
Can search for an document called **“Form 10-k”** which includes an annual report on 
1. Company location 
2. Top level management 
3. Potential risks
4. Financial data
5. Mergers and acquisitions 

## Social engineering 

Social engineering is an method to obtain information by building trust to obtain information about the target usually an employee working in the target company 

It can be accomplished in many ways 
1. Dumpster diving (it’s just as the term suggests )
2. Shoulder surfing (watching someone as they enter an information some also uses cameras )
3. Eavesdropping 
4. Phishing (it also has an type called spear phishing which targets an specific person whereas phishing is just general)
6. Pharming(same as phishing but uses websites instead of links )
7. Impersonation 

## Searching information about people 

Using public records by using names and narrowing the scope with the information you have beforehand 

Websites to use:
1. Anywho
2. Spokeo 
3. Zabasearch
4. Yansi 
5. Signal hire

Disclaimer: since the information in these websites may not be accurate it’s better to cross reference it with other sources or websites 
## Tracking online reputation 

Tracking an company online reputation is also crucial in footprinting 
By doing it you can come to know how the company operates ,does it have lazy employees ,lack of management skills, etc…

You can also use ftp search engine for digging up information on the target 

 Websites to use:
 1. Google image search
 2. Tineyes
 3. Google alerts 
 4. Pimeyes 

## Harversting email addresses

You can do this by finding the general way an company email is structured and find out the names of some employees working there and you their names in the structure and create an email list 

The structure can be found out via online or by contacting them asking for some information and when they reply you can your structure 

## Examining websites 

For an simple webpage you can see its source code through the browser but if it’s complex you can use an website mapper to understand its structure and find vulnerabilities in it 

## Websites Scraping

Downloading/scraping an website is done to look through the code for clues about the target like comments,passwords and you can also create an wordlist for an brute force attack 

Websites for scraping
1. HTTrack
2. Wget
3. Website ripper copier
4. Web data extractor

## Monitoring an website 

It is done to 
1. Understand the site behaviour 
2. Adhere to compliance 
3. Test to unauthorised changes
4. Reveals vulnerabilites

The websites to use:
1. Pingdom
2. Google website analytics
3. Up down.io
4. Monastic 
5. Quantcast

## Footprinting using DNS 



DNS can be vulnerable
1. Zone file compromise 
2. Cache poisoning 

Techniques used in DNS footprinting 
1. Zone transfer 
2. Reverse DNS lookup
3. Subdomain recovery 
4. Cache snooping 

## Examining an zone transfer 

An zone transfer is when an secondary dns server requests data from the primary server and the adversary somehow makes his server look like the one an secondary server 

How to avoid this 
1. Restrict zone transfer only to authorised servers 
2. Deny All req to port 53 
3. Using DNS security 

## Generating an domain name 

For launching an believable phishing attack 
Use an domain name generator which also checks if an domain is already in use or available (domain name analyser )

And after you buy an domain name you can get an TLS certificate from “letsencrypt.com”

## Determine the path

Assessing the network 
Sometime the device in an network does not have the required security to guard itself against attacks

CLI tools used 
1. Ping(used to test for reachablity)
2. Traceroute for Linux and tracert for windows (used to get to know the gateways an packet flows through before it’s reaching its destination by sending an special icmp packet)
3. Pathping (exclusive to windows which combines both ping and tracer) mtr (does the same thing as pathping)
4. Nslookup (used to diagnose DNS) you can use it in interactive mode 
         You can also get the same functionality form online websites
1. Domain information group(dig)used to query information bout an dns server 



## OSINT

Searching the Internet for valuable information bout the targets 

Tools used for osint 
1. Malteago
2. Shodan

## Investigating an email

Look for an email header from where you can get the ip addr form where it was sent and doing an reverse lookup you can the mail server where it originated from 

## VOIP Footprinting 

Is done to make sure that the voip systems in an organisation is not compromised or vulnerable to attacks Like 
1. Vishing(phishing but over voip)
2. Eavesdropping 
3. Id spoofing
4. Malware through software 

You can mitigate these threats by evaluating the voip servers if they are secure 

VoIP servers have an web interface so it can be vulnerable to SQL injections and DOS attacks 
Can check if it’s really secure by doing port scanning and banner grabbing 

Most of the times voip uses vpn to keep the calls protected so we should also check if the vpn service is secure 
1. Making sure they don’t use an obsolete ssl/tls ver
2. Use new vpn technologies like openvpn and wireguard
3. Check for dns data leaks

## Footprinting the deep and dark web 

While doing recon and footprinting also include the deep and dark web as you might also uncover some information about your target there 

But always be careful while surfing the dark web

Steps to take while surfing the dark web 
1. Use an Vm+vpn
2. Use a sock account 
3. Tor browser 

Other osint tool are:
1. Recondog 
2. Bill cipher 


