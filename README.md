# Software-Security
# Journal

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial was the client, this was a financial advisor company who needed to operate through an online application, so security measures needed to be taken to ensure customers' information was protected.

# What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I made good considerations regarding what areas of vulnerability needed to be addressed due to the type of business model of the company and the type of application created. It is important to code securely to ensure we are not adding or creating code that could be exploited by a hacker. Being aware of software security then is very importat for a company to ensure its private information remains protected from someone with intentions to cause any harm.

# What about the process of working through the vulnerability assessment did you find challenging or helpful?
The vulnerability assesment was somewhat simple but at the same time a little confusing as it didn't provide major information regarding the steps to be taken. The flow seem pretty straightforward but I wished the diagram showed a little more detail and showed examples of how to properly use it.

# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
To increase the layers of security I considered that information in rest and in transit should be encrypted, so even if an attacker were to see the information they wouldn't be able to understand it or do anything with it. One of the practices I would consider for future vulnerability assesments would be to run a dependency-check to analyze the type of vulnerabilities that have been discovered so far and see if possible solutions are available or if new libraries should be used instead.

# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
To ensure the application was functional I created a checksum test that would run on the local host through the https protocol. This protocol originally would consider the connection as insecure because no certificate authorities were validating my test app. After creating a selfsigned certificate and added it, the https protocol was able to verify the connection as secure. To ensure no vulnerabilities were added, I run the dependency check a second time and the results were the same as the first time.

# What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
One of the most helpful coding practice for me would be to run a dependency check to get a better picture of all the possible vulnerabilities that should be addressed. Also, creating a selfsigned certificate was very useful to test https communication was successful.

# Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would like to demonstrate that I am more aware of all the possible vulnerabilities that an attacker could exploit to get access or cause any kind of harm, and that I can increase the security of an application by analyzing the vulnerabilities in the dependencies, and ensure safer communications by enabling the https protocol.
