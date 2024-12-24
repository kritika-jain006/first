# OWASP TOP 10


### CHAPTER 1 :
OWASP stands for "Open Web Application Security Project" ,every 3-4 years it publishes the list of top ten most critical vulnerablities on web applications. Its provides guidance to the developers by updating the evolving threats.
#### Importance of owasp top 10:
-Provides to developers and security specialists knowledge about the primary risks that influence the programs.

-Offers a guideline way and equipment for detecting weakness in application development.

-Encourages global collaboration to tackle modern security challenges.


### CHAPTER 2 :

### Broken Access Control:  
It gives unauthorized users or attackers access to data, allowing them to see sensitive data or perform tasks which they are not supposed to. Broken Access Control is one of the most exploited vulnerabilities in web applications. 

For example: If someone finds a vulnerability in another person's account, they can make changes to that account, which is known as broken access control.

### CHAPTER 3:

### Cryptographic Failures:
Cryptography is the conversion of plain text into an encrypted text so that data cannot be seen by an unauthorized party. Cryptographic failures occur when a third party decrypts and exposes the sensitive information.

Some examples include- weak encryption,inadequate authentication.

### CHAPTER 4:

### Injection:
When attackers inject malicious data through input fields and the server is not able to sanitize or verify the data is called injection.This lead to unauthorized data access or manipulation.

Defence for preventing injection attacks is ensure and sanitize users input to avoid malicious data processing.

### CHAPTER 5:

### Insecure design:
Insecure design vulnerabilities occur in new software when security is not prioritized during the design phase, leading to weak or missing controls.

To prevent this, identify security threats and vulnerabilities early in the design phase.

### CHAPTER 6:

### Security misconfiguration:
Using protocols which are not secure, not configuring proper security in software or enabling unnecessary features leads to security misconfiguration.

Implementing https headers ,using complex passwords prevent these vulnerabilities.

### CHAPTER 7:

### Vulnerable and Outdated Components :
When software is not regularly updated or scanned, vulnerabilities may remain unaddressed, increasing the risk of exploitation.

Removing unknown or unnecessary data and files can help prevent this risk.

### CHAPTER 8:

### Identification and Authentication Failures:
This vulnerability occurs when attackers exploit flaws in the authentication mechanism, such as brute force attacks or weak session cookies. These flaws allow attackers to gain unauthorized access to another user's account.

Prevention- Using complex passwords, enforcing a lockout after certain attempts to avoid brute force attacks. 

### CHAPTER 9:

### Software and Data Intregity failures:
When the system fails to protect the consistant and accurate data, which leads to modifications in software. In this vulnerability attackers try to inject malicious data in the software.

Prevention:
Always use trusted sources for libraries and updates, ensuring they come from verified and secure origins.

### CHAPTER 10:

### Security Logging and Monitoring failures
these failures occur when systems fail to properly log security events or when monitoring processes are inadequate.

To prevent these failures use SIEM (Security Information and Event Management) to analyze logs.

### CHAPTER 11:

### Server-Side Request Forgery (SSRF):
Server-Side Request Forgery (SSRF) occurs when attackers manipulates a server to make internal or external resources request.Prevention- validate and sanitize user-supplied URLs.

### CONCLUSION:
The OWASP Top 10 is a crucial resource for identifying security risks in web applications. It emphasizes the importance of regularly updating security practices to defend against evolving threats.

### Refrences:
- [OWASP TOP 10](https://owasp.org/www-project-top-ten/)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/assets/archive/OWASP_Testing_Guide_v3.pdf)
- [OWASP wstg](https://github.com/OWASP/wstg)
- [OWASP Cheatsheet](https://github.com/OWASP/CheatSheetSeries)



