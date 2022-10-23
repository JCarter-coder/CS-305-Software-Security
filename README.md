# CS-305-Software-Security

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for their customers such as savings, retirement, investments, and insurance. They want to use the most current and effective software security for their modernization of operations.

# What did you do very well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?
After performing the static testing to identify security vulnerabilities, I was able to update Spring Boot to a current version.  This eliminated many of the vulnerabilities. Then I proceeded to analyze the remaining dependencies. Since the vulnerabilities were not applicable to the functionality of this program, I was able to suppress them before performing a final manual review.  It is important to code securely, especially when maintaining personal and financial information such as Artemis Financial. Compromise of security can negatively effect confidentiality, integrity, and availability of data. This will lead to costly financial repairs, long-term damage to the company's reputation, and decreased value of the company

# What part of the vulnerability assessment was challenging or helpful to you?
The most helpful part of running the vulnerability assessment was using the Dependency Check. The generated report is very detailed with all the necessary links to more information as well as the text to be utilized in suppression files.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I began by establishing a keystore and the HTTPS connection within the build. After running the program, static tests and manual reviews were performed.  It is important to understand how all the parts of the program allow data into or out of the system and the details of the vulnerable dependencies.  This allows you to determine potential threat vectors to address accordingly.  

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After checking the functionality of the software, static tests were performed to determine vulnerable dependencies that could be potentially updated. Once all concerning dependencies were up to date, a manual review was performed to see if the remaining vulnerabilities were relevant to the functionality of the system.  All refactoring was followed by the previous steps until the software was deemed secure.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The Maven Dependency report was especially useful.  This allowed focused attention to vulnerabilities within a java program.  Additionally, for in depth information, the NIST website provided a wealth of material on cryptographic modules and guidance.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I can demonstrate creating a keystore and storing certificates. In addition, I can establish a secure HTTPS connection in a browser.  Lastly, I can run a Maven Dependency check, analyze the produced report, and address as applicable. This includes updating dependencies as needed or suppressing irrelevant concerns to a project.
