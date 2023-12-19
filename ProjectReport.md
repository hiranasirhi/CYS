# CYS
## Cross-Site Scripting (XSS) Vulnerability in Markdown Rendering  
### What is XSS?  
Cross-site scripting (also known as XSS) is a web security vulnerability that allows an attacker to compromise the interactions that users have with a vulnerable application. It allows an attacker to circumvent the same origin policy, which is designed to segregate different websites from each other. Cross-site scripting vulnerabilities normally allow an attacker to masquerade as a victim user, to carry out any actions that the user is able to perform, and to access any of the user's data. If the victim user has privileged access within the application, then the attacker might be able to gain full control over all of the application's functionality and data.  
# Technical Details  
1. **Severity**  
High
2. **Affected Components**  
The variety of attacks based on XSS is almost limitless, but they commonly include transmitting private data, like cookies or other session information, to the attacker, redirecting the victim to web content controlled by the attacker, or performing other malicious operations on the user's machine.
3. **Attack Vector**  
In reflected XSS, the attack vector is inside the HTTP client request processed by the server. If the server's request and response are semantically related, the server's response is formed from the request data. For example, the request could be a search query and the response might be the results page.
4. **Impact**  
cross site scripting attack can severely impact websites and web applications, damage their reputation and relationships with customers. XXS can deface websites, can result in compromised user accounts, and can run malicious code on web pages, which can lead to a compromise of the user's device.


