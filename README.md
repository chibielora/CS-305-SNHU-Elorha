# CS-305-SNHU-Elorha
## Projects for Software Security at SNHU

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

An investment, insurance, and retirement portfolio management company, the client Artemis Financial assists clients with managing their portfolios. As part of their original requirements, they requested security for their software application to ensure compliance with government regulations as well as private security. Due to the potential financial risks involved, Artemis Financial is extra cautious when developing their new online presence.

- What did you do particularly well in identifying their software security vulnerabilities? Why is it critical to code securely? What value does software security add to a company’s overall wellbeing?

Identifying which plugins were responsible for most vulnerabilities using the assessment seemed to be my strongest skill while finding issues. The importance of coding securely is to ensure that your code won't be compromised by malicious software from third party entities and act as an instrument for stealing sensitive data from your clients' databases. Not only their reputation, but the whole business can be at stake if there isn't a well-secured and updated system working to their benefit.

- What about the process of working through the vulnerability assessment did you find challenging or helpful?

I tested multiple versions of plugins to ensure they wouldn't conflict with other packages. This was done until I was able to determine which specific versions I should be calling for in order to set my vulnerability counter to zero. The most challenging part was the fact that I had to work through most of it manually until the vulnerabilities expired. I did not need to suppress any vulnerabilities for the final project, but that is something I find somewhat tricky to determine when you are conducting the assessment. In a previous work we had to effectuate suppression and although I was able to fix it, it was still quite not very clear to me.

- How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

When dealing with APIs, increasing security can sometimes mean finding and solving easy fixes, such as modernizing the old APIs being used by the application. In cases where software updates cannot resolve vulnerabilities, it is necessary to code securely to resolve them directly. Depending on how often code changes are made, dependency reports may be checked daily, weekly, monthly even. Operating System updates are equally crucial, since the majority of attacks target operating systems rather than individual programs.

- How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

In addition to testing after every iteration, I also refreshed the dependency check to ensure that the vulnerability was addressed whenever the code was altered.

- What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

In addition to using Maven, I found that learning how to self-sign, validating the user's input, using HTTPS, and using CA were extremely helpful, and despite some hiccups during the process, I am now more confident about working on my own.

- Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

Installing and maintaining a Restful API proved quite helpful to me and I had never done it from the ground up like this before. After I have gone through the installation process a few times, I feel more comfortable if I need to showcase a project such as this to an employer.
