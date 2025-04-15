# Project2-CS305
<h2><strong>Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?</strong></h2>
<p>Artemis Financial is a consulting company that specializes in developing individualized financial plans, which include savings, retirement, investments, and insurance for its customers. Secure communications are critically important for Artemis because client data, such as financial information, social security numbers, and investment details, must be protected to maintain client trust and comply with industry regulations. Futhermore, they need to us to check for vulneribilitied within the system and check for weaknesses that could compromise data security. The primary concerns included safeguarding client information, maintaining regulatory compliance, and securing the application from external threats. The company specifically wanted an evaluation of their input validation, API security, encryption mechanisms, and dependency vulnerabilities to prevent unauthorized access and data breaches.
</p>

<h2><strong>What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?</strong></h2>
<p>I implimented a dependacy check report. In addtion, its important to code securely, because you can run into vulnerabilities that could potetnailly comprimise the deisgn of of the system and have customer data leaked. Moreover, software security is very importnat for the well being because users can trust that their data is secured.  </p>

<h2><strong>Which part of the vulnerability assessment was challenging or helpful to you?</strong></h2>
<p>What was helpful for me for the vulneribility assesssment is being able to see what exactly could be a issue and giving a description of what it was. Howver, it was challenging since the code didn’t have clear documentation or comments, I had to spend extra time understanding how different parts of the application interacted, especially the API endpoints and how user input was processed.</p>

<h2><strong>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</strong></h2>
<p>I will recommend SHA-256 because it has the lowest chance of collision. In addition, it is a secure cryptographic hash function designed to be collision-resistant. SHA-256 produces a fixed-size 256-bit (32-byte) hash, ensuring that even a small change in input results in a vastly different output. This makes it ideal for verifying file integrity and detecting tampering. It is widely supported in Java through the MessageDigest class and is a standard choice for checksum verification due to its strength, efficiency, and widespread adoption.I would also recommend future code reviews. 
</p>

<h2><strong>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
</strong></h2>
<p>I conducted a secondary static vulnerability scan using the OWASP Dependency-Check tool to confirm that no new vulnerabilities were introduced. I compared the before-and-after reports to ensure that the identified issues were resolved and no additional risks appeared due to the changes. I also executed the application to verify that it still ran without errors and performed its intended functions correctly.</p>

<h2><strong>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
</strong></h2>
<p>I used eclipse as my ede, and installed maven to run my project and run a dependancy check to check for vulnerabilities. Moreover, I docusmented my findings. In addition, to using these tools, I followed secure coding practices such as reviewing input handling, identifying improper error handling, and evaluating API exposure. I also documented each vulnerability and categorized them by severity, which helped prioritize remediation efforts and would be useful for future risk assessments.</p>

<h2><strong>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
</strong></h2>
<p>I would showcase my ability to identify and document security vulnerabilities in a real-world Java application. This includes both manual code review and automated static analysis using industry-standard tools like OWASP Dependency-Check. I would also highlight my ability to interpret the results, prioritize risks, and recommend appropriate mitigation strategies.

Additionally, I can demonstrate my understanding of secure coding practices, such as input validation, encryption standards, and secure API design. My documentation from this assignment reflects not just technical knowledge, but also clear communication—skills that are valuable in both development and cybersecurity roles.</p>
