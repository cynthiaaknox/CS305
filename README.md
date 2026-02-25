# CS305
CS305

Q: Briefly summarize your client, Artemis Financial, and its software requirements. 
A: Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance. Artemis Financial wanted to modernize their software by using the latest and most effective software security. 

Q: Who was the client? 
A: The client is Artemis Financial.

Q: What issue did the company want you to address?
A: They have requested our assistance to modernize their software, and to assess security vulnerabilities. They also asked us to identify an algorithm that needed to be decrypted with a secret key and can be used for encrypting their archive files. Finally, they have requested us to add a file verification step to their web application to ensure secure communications. When the web application is used to transfer data, the company will need a data verification step in the form of a checksum.

Q: What did you do well when you found your client’s software security vulnerabilities? 
A: Both reviewing the code manually as well as running the OWASP Dependency Check identified what dependencies need to be upgraded and what changes need to be applied to the software to secure it.

Q: Why is it important to code securely? 
A: Securing code is of utmost importance to prevent release of sensitive customer data, which could cost the company penalties and worse yet, exposing customer private data could expose them to loss of funds and privacy.

Q: What value does software security add to a company’s overall well-being?
A: Securing software allows the company to expand its client base, helping more clients to prosper, growing revenue and employing more people.

Q: Which part of the vulnerability assessment was challenging or helpful to you?
A: The most difficult for me was the certificate deployment and testing locally. Confirming that the proper protocol, HTTPS was actually securing the application AND being able to bypass the "Not Secure" flag locally was a huge challenge.

Q: How did you increase layers of security? 
A: Implementation of the hashing function, the certificates, running the manual code checks, the REST API endpoint as well as running the OWASP Dependency Check all served to secure the application.

Q: In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
A: I would run the OWASP Dependency Check, and either upgrade or address code changes as specified in the CVE.

Q: How did you make certain the code and software application were functional and secure? 
A: I re-ran the OWASP Dependency Check and accessed the REST API endpoint to confirm it was accessible and secure.

Q: After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
A: Again, as stated in the previous question, re-running the OWASP Dependency Check and accessed the REST API endpoint to confirm it was accessible and secure.

Q: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
A: Again, the OWASP Dependency check, certificate generation as well as code reviews.

Q: Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
A: I would probably show the Project Two document as it was the most difficult assignment!
