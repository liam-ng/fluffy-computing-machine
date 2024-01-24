# Lesson Learned from Security Breaches
Cybersecurity Breaches for Payment Industry (Billtrust &amp; Fiserv)
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/38f20222-9e3b-48f7-9af2-760c88dfe34e)
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/b9e0a603-aceb-450d-b606-30a890362ad5)
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/7e4f0cae-fa63-4192-95af-ac7d83d9c634)
Rapid7's full technical analysis of the exploit chain for CVE-2023-34362 https://attackerkb.com/topics/mXmV0YpC3W/cve-2023-34362/rapid7-analysis?referrer=etrblog

![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/3b7c11c8-d3cc-4699-9234-4f38b8121d31)
A strong IOC may be present in the log file C:\MOVEitTransfer\Logs\DMZ_WebApi.log

Ref 1 MOVEit Transfer Critical Vulnerability (May 2023) (CVE-2023-34362) https://community.progress.com/s/article/MOVEit-Transfer-Critical-Vulnerability-31May2023

Ref 2 Rapid7 Observed Exploitation of Critical MOVEit Transfer Vulnerability https://www.rapid7.com/blog/post/2023/06/01/rapid7-observed-exploitation-of-critical-moveit-transfer-vulnerability/

Ref 3 MOVEit Transfer Critical Vulnerability CVE-2023-34362 Rapid Response https://www.huntress.com/blog/moveit-transfer-critical-vulnerability-rapid-response

Ref 4 AttackerKB CVE-2023-34362 https://attackerkb.com/topics/mXmV0YpC3W/cve-2023-34362/rapid7-analysis?referrer=search
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/7d1fb9e1-0af5-486a-81d8-5bee17cc148e)

![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/44cf0406-3a15-48e7-918f-93d0078c35eb)
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/fc561669-cc7c-4a96-939a-5a5fe8c36af2)

# Appendix 
## Opportunities for Potential Improvement:

- [AWS IAM user bulk key rotation](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/automatically-rotate-iam-user-access-keys-at-scale-with-aws-organizations-and-aws-secrets-manager.html)

- [Identify unused IAM roles with AWS Config](https://aws.amazon.com/blogs/security/continuously-monitor-unused-iam-roles-aws-config/) and remove regularly

- [Identify unnecessary permissions on other resources](https://aws.amazon.com/blogs/security/automate-analyzing-permissions-using-iam-access-advisor/) and review regularly

- Privilege Access Management (CyberArk PAM) for machine-level access control
![image](https://github.com/liam-ng/fluffy-computing-machine/assets/90180576/2b5d667c-8e3e-4a7d-9d5b-da1e1993b311)

- Assess security measures in place against [OWASP Principles of Security](https://owasp.org/www-project-developer-guide/draft/04-foundations/03-security-principles)
- Assess design against Baseline Security Assessment on [AWS](https://github.com/aws-solutions-library-samples/guidance-for-baseline-security-assessment-on-aws)
- Identify attack vector (if any) with reference to [OWASP Top Ten](https://owasp.org/www-project-top-ten/), [SANS Top 25](https://www.sans.org/top25-software-errors) and [OWASP Application Security Verification Standard (AVAS) Level 3](https://github.com/OWASP/ASVS)
- Prioritize threat in team discussion with reference to [OWASP Risk Rating](https://owasp.org/www-community/OWASP_Risk_Rating_Methodology) and business & technical context

## Interesting Tools
- [Threagile](https://threagile.io/)Threat Modelling diagrams and report generator
- [PenTestGPT](https://github.com/GreyDGL/PentestGPT) – an interactive Pentest tool (identification) support any LLMs

## Interesting Stats
- Data breach = [Loss of $180 per record with PII](https://purplesec.us/resources/cyber-security-statistics/)
