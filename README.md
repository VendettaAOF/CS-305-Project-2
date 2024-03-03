# CS-305-Project-2

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting firm. To stay competitive, they needed to build secure software that verified the data being served on their web application. By creating a checksum the data can then be verified. 
What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
After choosing a checksum algorithm cipher, I could test to ensure that any sent data was encrypted and secure. I then created an SSL self-signed certificate to facilitate the secure transfer of data.
What part of the vulnerability assessment was challenging or helpful to you?
Since the certificate I created was self-signed I couldn’t get my browser to recognize it as “safe”. This created an issue where I knew my solution should be secure, but my browser wasn’t reflecting the exact results I was expecting. 
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Using the dependency check report, I was able to suppress any false positives, and then start tackling each remaining vulnerability one by one. 
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
As I moved through the list of vulnerabilities I was attempting to resolve, I would continue to run tests to make sure I hadn’t introduced any new vulnerabilities into the code.
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The documentation on the dependency check report helped me to create the correct code structures. I also used documentation on Spring since the SSL server ran on that framework. 
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show them my understanding of the SHA-256 cipher algorithm. As well as my understanding of generating certificates, and commands for the Java Keystore.
