### Welcome to the OWASP Top 10 2010

OWASP Top 10 2010 List :

[A1-Injection](https://www.owasp.org/index.php/Top_10_2010-A1-Injection)

Injection flaws, such as SQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing unauthorized data.

[A2-Cross Site Scripting (XSS)](https://www.owasp.org/index.php/Top_10_2010-A2-Cross-Site_Scripting_(XSS))

XSS flaws occur whenever an application takes untrusted data and sends it to a web browser without proper validation and escaping. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.

[A3-Broken Authentication and Session Management](https://www.owasp.org/index.php/Top_10_2010-A3-Broken_Authentication_and_Session_Management)

Application functions related to authentication and session management are often not implemented correctly, allowing attackers to compromise passwords, keys, session tokens, or exploit other implementation flaws to assume other users’ identities.

[A4-Insecure Direct Object References](https://www.owasp.org/index.php/Top_10_2010-A4-Insecure_Direct_Object_References)

A direct object reference occurs when a developer exposes a reference to an internal implementation object, such as a file, directory, or database key. Without an access control check or other protection, attackers can manipulate these references to access unauthorized data.

[A5-Cross Site Request Forgery (CSRF)](https://www.owasp.org/index.php/Top_10_2010-A5)

A CSRF attack forces a logged-on victim’s browser to send a forged HTTP request, including the victim’s session cookie and any other automatically included authentication information, to a vulnerable web application. This allows the attacker to force the victim’s browser to generate requests the vulnerable application thinks are legitimate requests from the victim.

[A6-Security Misconfiguration](https://www.owasp.org/index.php/Top_10_2010-A6-Security_Misconfiguration)

Good security requires having a secure configuration defined and deployed for the application, frameworks, application server, web server, database server, and platform. All these settings should be defined, implemented, and maintained as many are not shipped with secure defaults. This includes keeping all software up to date, including all code libraries used by the application.

[A7-Insecure Cryptographic Storage](https://www.owasp.org/index.php/Top_10_2010-A7-Insecure_Cryptographic_Storage)

Many web applications do not properly protect sensitive data, such as credit cards, SSNs, and authentication credentials, with appropriate encryption or hashing. Attackers may steal or modify such weakly protected data to conduct identity theft, credit card fraud, or other crimes.

[A8-Failure to Restrict URL Access](https://www.owasp.org/index.php/Top_10_2010-A8-Failure_to_Restrict_URL_Access)

Many web applications check URL access rights before rendering protected links and buttons. However, applications need to perform similar access control checks each time these pages are accessed, or attackers will be able to forge URLs to access these hidden pages anyway.

[A9-Insufficient Transport Layer Protection](https://www.owasp.org/index.php/Top_10_2010-A9-Insufficient_Transport_Layer_Protection)

Applications frequently fail to authenticate, encrypt, and protect the confidentiality and integrity of sensitive network traffic. When they do, they sometimes support weak algorithms, use expired or invalid certificates, or do not use them correctly.

[A10-Unvalidated Redirects and Forwards](https://www.owasp.org/index.php/Top_10_2010-A10-Unvalidated_Redirects_and_Forwards)

Web applications frequently redirect and forward users to other pages and websites, and use untrusted data to determine the destination pages. Without proper validation, attackers can redirect victims to phishing or malware sites, or use forwards to access unauthorized pages.
