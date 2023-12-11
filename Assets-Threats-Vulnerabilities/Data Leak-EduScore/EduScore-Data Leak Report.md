# Analyze the Incident
***What factors contributed to the information leak?***

1. This company does not prioritize training to promote a strong security posture.

2. Access to the internal folder was not limited to the sales team and the manager.

3. The business partner should not have been given permission to share the promotional information to social media.

# Review Data Privacy Controls
***How does NIST address least privilege?***

[NIST SP 800-53: AC-6](https://csrc.nist.gov/projects/cprt/catalog#/cprt/framework/version/SP_800_53_5_1_0/home?element=AC-6): Addresses how an organization can protect their data privacy by implementing least privilege. It also suggests control enhancements that can be used to improve the effectiveness of least privilege in an organization. 

**NOTE**: You can find information on NIST publications by navigating through their [Cybersecurity and Privacy Reference Tool (CPRT)](https://csrc.nist.gov/projects/cprt/catalog#/cprt/home)

# Recommend Control Enhancements
***What could be utilized to improve the principle of least privilege at EduScore?***

1. Log the execution of privileged functions.
2. Prohibit privileged access to the system by non-organizational users.
3. Review the privileges assigned to organization-defined roles or classes of users to validate the need for such privileges; and reassign or remove privileges, if necessary, to correctly reflect organizational mission and business needs.

# Justify Recommendations
***How might these improvements address the issues?***

To enhance the principle of least privilege at EduScore, a number of key controls can be implemented. First, logging the execution of privileged functions facilitates ongoing monitoring and auditing, enabling the rapid detection of unauthorized or suspicious activities. Regular reviews of these logs enhance transparency and accountability, helping organizations respond swiftly to potential security incidents. Second, prohibiting privileged access to the system by non-organizational users involves implementing clear access policies and robust authentication mechanisms. By consistently updating user access controls and conducting periodic reviews, organizations can maintain a secure access environment that aligns with their evolving business landscape. Additionally, reviewing and adjusting privileges assigned to defined roles ensures that access rights are continually validated, minimizing the risk of misuse and adhering to the principle of providing the least necessary access for effective job performance. I recommend EduScore implement all of these controls to enhance its future security posture, significantly reducing the likelihood of a recurring data leak.
