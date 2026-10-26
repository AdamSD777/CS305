# CS305
Portfolio for CS305 at SNHU

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
    For this class, I had to perform security tasks on a program for "Artemis Financial", a financial services company. It wanted its "web application" to protect customer data, so I added a checksum for data integrity and switched the app from HTTP to HTTPS.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
    I reviewed the code by hand and ran dependency-check, then used standard algorithms (SHA-256, RSA-2048) instead of making my own.

Which part of the vulnerability assessment was challenging or helpful to you?
    I found the hardest part to be manually reviewing the code. It can be hard to parse through an unfamiliar program to find the relevant information.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    I mostly focused on using "NIST" layers of security, and found their resources most helpful in assessing vulnerabilites for mitigation.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    I ran the app, compared the checksum with a second tool, and reviewed the code by hand. After refactoring, I ran dependency-check again and confirmed that I had added no new dependencies or findings.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    Keytool, Maven, dependency-check, and the Java standard library (MessageDigest) were all useful.
    
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    I would show the refactored project (HTTPS plus the SHA-256 checksum) and the secure coding report. Together they show I can find vulnerabilities, fix them, and explain the reasons.
