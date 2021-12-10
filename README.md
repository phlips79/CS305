# CS305
SNHU CS-305 Software Security

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a financial management company that assists their clients with management of their investment, insurance, and retirement portfolios. Their request for support involved securing their software application to make it not only more secure but also to ensure compliance with financial regulations.

**What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

What I did well was analyzing the application against the current threat vector to determine which areas should be refactored. My experience in CyberSecurity for the Federal Government and my work with Approvals To Operate, vulnerability scanning, and vulnerability remediation was a great resource for accomplishing these tasks.

It's important to code securely becuase there are an infinite number of ways for a malicious user to infiltrate software and applications, and exfiltrate data and cause harm to customers and companies. The recurring theme that was brought up every week in class was primarily use rinput validation and how weak validation can lead to attacks like Cross Site Scripting and SQL Injection.

Software security is one of the most critical components of any company's digital presence in the modern age. eCommerce is a major part of our lives, and with that is the confidence of the customers using those digital platforms. If a company's network or database are breached, it can destroy their reputation with customers who may leave for another company. In addition, downtime caused by attacks or buggy software also causes financial harm to companies. Limiting their threat vectors and retaining customer trust is crucial for any company in the digital realm.

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**

It's always challenging dealing with Eclipse because it is such an advanced and powerful tool. And although we as students have been introduced to Maven, there are so many intricacies to it that it can be very difficult to work with since it has a steep learning curve. In addition, Java isn't the easiest language to learn, so refactoring code in Java can be challenging at times.

What I found helpful was relying on my Cybersecurity background and familiarity with CVEs to navigate their meaning and find their resolutions.

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**

As is usually the case in the real world, I found that increasing security - especially when dealing with APIs - is usually an issue of low hanging fruit, such as modernizing old APIs. If vulnerabilities cannot be remediated by updating software, then we need to delve into the meat of the vulnerability and see how to code securely to resolve the vulnerability.

In the future, I will be continually checking dependency reports on a weekly basis, possibly nightly depending on often the code is changed. In addition, staying on top of Operating Systems updates is a major area of security since most attacks are targeted at the OS, and less frequently on individual applications.

**How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?**

After I refactored code, I ran the application to ensure it still functioned as intended. In other words, I tested after every iteration. In addition to testing, I also re-ran the dependency check every time to ensure that the vulnerability was remediated.

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**

The Mave dependenncy check was the biggest take away from this class for me. I will definitely be utilizing it for all Java applications I develop in the future.

**Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?**

I chose to upload our final project, but it demonstrated not only an understanding of encryption algorithms but it showcased my coding abilities, security mindset, and understanding of operating systems, browsers, and the security components that operating in the background like SSL certificates and ports.


