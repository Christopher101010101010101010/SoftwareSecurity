# SoftwareSecurity
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
For this project, I am working for Global Rain, a software engineering company, as a software consultant to Artemis Financial that is a global financial consultant firm 
  that specializes in developing savings, retirement, investment and insurance plans. During this project, I am working to modernize Artemis Financial's software security for one of their 
  web applications that includes determining the appropriate encryption algorithm cipher to encode the application's data and integrate a checksum.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
After determing the system's vulnerabilities I determined where bootstrapped software needed to be updated in references along with the best algorithm cipher to utilize when encrypting network data. 
  The importance of coding for security cannot be stressed enough as inadequately encrypted data transfered across a network may be hacked and exposed that would protentially reveal confidential 
  client information, employee information, business strategies or company products inevitably costing Artemis Financial the public's trust and unpredicatable levels of profits. 

What part of the vulnerability assessment was challenging or helpful to you?
I found it to be difficult to integrate the keystore JKS file into the application but also found this task very informative as I reviewed various controls for the command prompt interface,
  where keystores and certificate authorities are generated.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Initially, I focused upon implementing code with the principle of Encapsulation, Quality of Coding and Cryptography. Next, I increased the layers of security by introducing a checksum, certificate
  authority/keystore and confirmed that all bootstrapped application software was up-to-date. In the future, I will definitely utilize the Maven Dependency-Check plug-in to determine weak points within
  an application and implement the appropriate encryption algorithm cipher dependent upon the application's operating environment.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To confirm that the application was functional and secure upon refactoring the code a secondary Mavien Dependency-Check was run to ensure new vulnerabilities were not introduced and existing 
  vulnerabilities were mitigated. After this step, the application was booted to confirm smooth operation and termination.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
There are several resources that were paramount to the success of this application, such as the Spring Boot plug-in, the Mavien Dependency-Check plug-in and the Java Security Standard
  documentation on Oracle's website.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this application, I would present an empolyeer with examples of proper implementation of the AES algorithm cipher, implementationed of a trusted keystore for network authentication, utilization
  of a dependency check to observe vulnerabilities due to an applications reference to bootstrapped software packages and quality coding technique.
