# Running commands and seeing output when typing google.com

## A complete step-by-step of writing commands and seeing the resulting outputs when typing google.com in the browser

### This project demonstrates what happens when you type "https://www.google.com" in your browser and press Enter

* Retrieving different protocol information in PowerShell when typing google.com into the browser

* Explanation for the output in Powershell when typing google.com into the browser.

#### Step by Step Instructions:

DNS Server Resolution

*Type the following PowerShell command to verify DNS resolution for google.com.

**Output Explanation:
The output confirms that the DNS server successfully resolves google.com to one or more IP addresses, allowing the client to locate the Google server.

TCP/IP Client–Server Connection

Type the following command in PowerShell to verify a TCP/IP connection to google.com.

Output Explanation:
The output confirms that a TCP connection to google.com on port 443 succeeds, indicating that the client can securely reach Google.

Firewall Access Verification

Type the following command in PowerShell to test whether the client request is allowed through the Google edge firewall.

Output Explanation:
The output confirms that Google’s firewall allows the client request to access the website.

HTTPS Protocol Verification

Type the following command in PowerShell to verify that google.com uses HTTPS on port 443.

Output Explanation:
The output confirms that google.com is accessible using the HTTPS protocol on port 443.

TLS Certificate Verification

Type the following command(s) in PowerShell to create a secure connection and retrieve Google’s TLS certificate.

Output Explanation:
The output confirms that Google presents a valid and trusted TLS certificate, ensuring encrypted communication.

Load Balancer Traffic Distribution

Type the following command in PowerShell to verify continuous traffic handling by Google’s load balancer.

Output Explanation:
The repeated successful responses indicate that traffic is consistently distributed, which is characteristic of a properly functioning load balancer.

Web Server Availability

Type the following command in PowerShell to verify that Google’s web server is operational.

Output Explanation:
The output confirms that Google’s web server responds successfully to client requests.

Dynamic Application Load Verification

Type the following command(s) in PowerShell to verify that dynamic applications for google.com can be loaded.

Outcome Explanation:
The output confirms that application resources required for dynamic functionality are accessible, verifying that applications can be loaded from the google.com server.





























##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.
