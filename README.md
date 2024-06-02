# Prevention of Phishing Websites

## ABSTRACT
Phishing is a new type of network attack where the attacker creates a copy of an existing web page to fool users in to submitting personal, financial, or password data to what they think is their service provider’s website. 
This information can be used for future target advertisements or even identity theft attacks (e.g., transfer money from victims' bank account). 
The frequently used attack method is to send e-mails to potential victims, which seemed to be sent by banks, online organizations, or ISPs.
In these e-mails, they will make up some causes, e.g. the password of your credit card had been mis-entered for many times, or they are providing upgrading services, to allure you visit their Web site to conform or modify your account number and password through the hyperlink provided in the e-mail. 
If you input the account number and password, the attackers then successfully collect the information at the server side, and is able to perform their next step actions with that information (e.g., withdraw money out from your account). 

## EXISTING SYSTEM
Detect and block the phishing Web sites in time: If we can detect the phishing Web sites in time, we then can block the sites and prevent phishing attacks. It's relatively easy to (manually) determine whether a site is a phishing site or not, but it's difficult to find those phishing sites out in time.
Enhance the security of the web sites: The business Websites such as the Web sites of banks can take new methods to guarantee the security of users' personal information. One method to enhance the security is to use hardware devices. 
Another method is to use the biometrics characteristic (e.g. voice, fingerprint, iris, etc.) for user authentication. For example, PayPal had tried to replace the single password verification by voice recognition to enhance the security of the Web site. 
The phishers hide their identities when sending the spoofed e-mails, therefore, if anti-spam systems can determine whether an e-mail is sent by the announced sender (Am I Whom I Say I Am?), the phishing attacks will be decreased dramatically.

## DRAW BACKS OF THE EXISTING SYSTEM
Phishing is one of the major threats in this internet era. Phishing is a smart process where a legitimate website is cloned and victims are lured to the fake website to provide their personal as well as confidential information, sometimes it proves to be costly. 
Though most of the websites will give a disclaimer warning to the users about phishing, users tend to neglect it. 
It is not a fully responsible action by the websites also and there is not much that the websites could really do about it. 
Since phishing has been in persistence for a long time, many approaches have been proposed in past that can detect phishing websites but very few or none of them detect the target websites for these phishing attacks, accurately.

## SOFTWARE SPECIFICATION                     
1. Operating System		: Windows 10 and above
2. Front end			: ASP.NET
3. Back end			: MS SQLSERVER

## HARDWARE SPECIFICATION
1. PROCESSOR	  :	Dual Core and above
2. HARD DISK	  :	256 GB
3. RAM  		  :	2 GB
4. MONITOR	  :	15” Color Monitor 
5. KEYBOARD	  :	104 keys Standard Keyboard
6. MOUSE		  :	Standard 3 Button Mouse

## MODULE DESCRIPTION
1. Web Crawler:
   - Admin can use this module.
   - In this module he gives some use of the website.
   - It will crawl the links  inside that website.
   - If it is  a Phishing website/user, it will added to the black list.
   - Because the phishing website does not contain any links.
2. View Blacklist
   - The admin can view the blacklisted websites/users.
   - However original users and malicious user may not know whether they have been tracked for their IP address and other details of time etc.,
   - It is an indirect way of observation.

3. Check website/user:
   - The user will access this module.
   - In this module user can enter the URI of the website, To check if it is in the black listed user/website or not the website/user is in the blacklist.
   - Then it will give an notify alert message.
