# Network-Hardening-Analysis
<h1>Description</h1>

In this exercise, I am presented with a scenario involving a social media organization that has recently suffered a significant data breach due to undetected vulnerabilities. My task is to address this breach by identifying common network hardening tools that can be applied to enhance the organization's overall security. Subsequently, I will pinpoint a specific vulnerability within the company and propose various network hardening techniques to mitigate it. Lastly, I will elucidate how the chosen methods and tools will effectively manage the vulnerability and proactively prevent future breaches.

Based on my knowledge about network hardening and security-related practices, such as port filtering, network access controls, and encryption protocols for safeguarding network communications, these network hardening practices empower organizations to proactively monitor potential threats and thwart certain attacks from compromising their networks. Some of these measures are implemented as routine safeguards, while others are periodically enacted, such as bi-weekly or monthly reviews. Proficiency in utilizing network hardening tools and methodologies has equipped me with the capability to vigilantly monitor network activities and fortify an organization's network against a spectrum of potential threats.


<h2>Scenario</h2>

Review the scenario below.

You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future.

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:
    -  The organization’s employees' share passwords.
    -  The admin password for the database is set to the default.
    -  The firewalls do not have rules in place to filter traffic coming in and out of the network.
    -  Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 


<h3>Security risk assessment report </h3>

I would strongly suggest three hardening tools and methods to implement that can improve the security of their systems:

    -  Firewall Maintenance: It is crucial to conduct regular security configuration checks and updates to mitigate vulnerabilities. Proactively maintaining the firewall allows for effective threat prevention. Additionally, updating firewall rules to filter both incoming and outgoing network traffic is a pivotal component of this approach. Whenever a security event, particularly one that permits suspicious network traffic into the system, occurs, firewall rules should be promptly updated. This measure serves as a formidable defense against various types of Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks.
    -  Password Policies: Enforcing rigorous password policies for all employees is essential to safeguard the confidentiality of their passwords and discourage attackers from easily guessing or cracking user passwords. Establishing and enforcing a password policy within the organization significantly raises the difficulty level for malicious actors attempting to gain network access. Regular enforcement of the password policy rules is imperative to enhance user security continually.
    -  Multifactor Authentication (MFA): Implementation of MFA mandates that users validate their identity through two or more authentication methods before accessing the system or network. These authentication methods can encompass passwords, PINs, badges, one-time passwords (OTPs) sent to mobile phones, fingerprints, and more. The adoption of MFA substantially reinforces network access security. Regularly enforcing MFA helps reduce the likelihood of malicious actors gaining access through brute force or related attacks. It also mitigates the risk of password sharing within the organization, particularly among personnel with administrator-level privileges on the network.
