---
author:
  - Anthony Stulens
title: Offensive Security Training Opportunities - Part 2
date: 2025-10-15
description: Article giving an overview of offensive training opportunities in 2025.
summary: An overview of offensive training opportunities in 2025. Focus on Web, API & Mobile Pentesting.
tags:
  - Training
  - Certification
  - Offensive
  - Security
  - OffSec
  - HackTheBox
  - INE-Security
  - Portswigger
  - SANS
  - Pentesting
  - APISEC-University
  - Agarri.fr
  - MobileHackingLab
  - Synacktiv
  - Web-Pentesting
  - Mobile-Pentesting
ShowToc: true
TocOpen: false
cover:
  image: ""
  alt: Ethical hacking training
  caption: Ethical hacking Training
---

![banner](/images/banners/20251008-Offensive_security_training_opportunities_2025_part2.png)

## Intro
Welcome back to the series on *Offensive Security Training Opportunities in 2025*. In Part 1, I covered general pentesting training platforms, certifications, and courses that will help you get a foothold in the field or sharpen your skills as a pentester.

In this second installment, we’ll focus on training resources dedicated to web, API, and mobile application security. While some of the courses included in this list are suitable for beginners, it’s recommended to start with the foundational material before diving into the more specialized topics.

This post is Part 2 of the *Offensive Security Training Opportunities in 2025*. You can find the other posts in the links below:

- [Part 1: General Pentesting](/posts/offensive-security-training-opportunities-in-2025-part-1)
- [Part 2: Web/API & Mobile Pentesting (This)](#)
- [Part 3: Red & Blue Teaming (COMING SOON)](/posts/offensive-security-training-opportunities-in-2025-part-3-red-and-blue-teaming/)

**Disclaimer:** The opinions stated in this article are solely my own and do not necessarily reflect those of my employer or other affiliations I have/had. Next to that, courses are not listed in a specific order (this is no ranking by any means). Just because a course is listed in my post does not mean I have actively taken or bought the course, although I have participated in many of these and plan on taking more from this list.

### TL;DR
If you are only interested in a summary, I have included a table at the end of every chapter with the necessary information.   
- [Web (&API) Pentesting Overview](#overview)
- [Mobile Pentesting Overview](#overview-1)

## Web (& API) Pentesting
Web and API training courses are valuable for pentesters looking to specialize in application security or expand beyond general infrastructure testing. This list includes hands-on labs, structured courses, and certification options that emphasize real-world attack scenarios and modern web technologies. Although some of them are beginner-friendly, a solid understanding of basic pentesting concepts is recommended before diving into these topics.

### PortSwigger
{{< figure src=/images/training-blogpost/PortSwigger.png  align=center >}}
"The best-in-class software and learning for security engineers and penetration testers".

#### [Portswigger Academy](https://portswigger.net/web-security) 
PortSwigger Academy offers **free** course content on web application vulnerability topics including iterative labs to complete. The content is continuously updated, with new topics/labs are added regularly.

##### Cost
Free

#### [Burp Suite Certified Professional (BSCP)](https://portswigger.net/web-security/certification)
Based on the topics covered in their Academy, PortSwigger offers a standalone web application pentester certification. The exam is pretty hard giving you only 4 hours to completely pwn 2 web applications; however, no report is needed. It is recommended that you complete all practitioner level labs in the academy and do their practice exam. This is a must have for any web application penetration tester!
{{< figure src=/images/training-blogpost/bscp.png  align=center width="30%">}}

##### Cost
$90 for 1 exam voucher

### Hack The Box
{{< figure src=/images/training-blogpost/HTB-logo.png  align=center >}}
Via their academy platform HTB offers 2 web focused certifications:

#### [HTB Certified Web Exploitation Specialist (CWES)](https://academy.hackthebox.com/preview/certifications/htb-certified-bug-bounty-hunter)
The CWES (FKA Certified Bug Bounty Hunter - CBBH) is an entry-level / intermediate web pentesting certification. It focuses on technical competency in the web application penetration testing and bug bounty domains. It focuses on black-box testing techniques. Course completion is required to start the exam.
{{< figure src=/images/training-blogpost/htb-cwes.png  align=center width="30%">}}

##### Cost
To access the CWES course, only the Silver subscription is required. This costs €410/year (excl. VAT), including 1 exam voucher + 1 free retake

#### [HTB Certified Web Exploitation Expert (CWEE)](https://academy.hackthebox.com/preview/certifications/htb-certified-web-exploitation-expert)
The CWEE is an advanced web pentesting certification. It covers more advanced web attacks and also focuses more on white-box techniques. Course completion is required to start the exam.
{{< figure src=/images/training-blogpost/htb-cwee.png  align=center width="30%">}}

##### Cost
To access the CWEE course, a gold subscription is required. This costs €1.055/year (excl. VAT), including 1 exam voucher + 1 free retake

### INE Security
{{< figure src=/images/training-blogpost/inesecurity_logo.jpeg align=center width="30%" >}}
As part of their cyber training offering, INE offers the following web training + certifications: 

#### [INE Security Web Application Penetration tester (eWPT)](https://security.ine.com/certifications/ewpt-certification/) 
The eWPT covers essential web vulnerabilities and how to exploit them. This is assessed in a multiple-choice exam, in which you must conduct tests in a hands-on lab and then answer questions within 10 hours.
{{< figure src=/images/training-blogpost/eWPT.png align=center width="30%" >}}

##### Cost
$599 for 3 months of premium pass* access + 1 exam attempt + 1 free retake. Afterwards, it's $749 for the Premium pass annually. 
The premium pass gives access to INE's entire content library.

#### [INE Security Web Application Penetration Tester eXtreme (eWPTX)](https://security.ine.com/certifications/ewptx-certification/)
The eWPTX continues where the eWPT left off. Covering more advanced techniques in the web application security domain focusing on topics such as WAF evasion and custom exploit development. The eWPTX is INE's most advanced web penetration tester certification.
{{< figure src=/images/training-blogpost/eWPTX.png align=center width="30%" >}}

##### Cost
$599 for 3 months of premium pass* access + 1 exam attempt + 1 free retake. Afterwards, it's $749 for the Premium pass annually. 
The premium pass gives access to INE's entire content library.

### OffSec
{{< figure src=/images/training-blogpost/offsec-logo.png align=center >}}
OffSec currently offers 2 web pentesting trainings/certifications:

#### [Offensive Security Web Assessor (OSWA)](https://www.offsec.com/courses/web-200/)
The OSWA covers foundational skills necessary to execute professional web application assessments. It covers essential techniques for identifying and exploiting XSS, SQL Injection, SSRF, and more. The course is geared towards entry-level to intermediate web attacks in black-box fashion. 
{{< figure src=/images/training-blogpost/oswa.png align=center width="30%">}}

##### Cost
The course is available in different pricing:
- Standalone course: including 1 exam attempt, including 90 days lab access ($1.749)
- Learn One annual subscription: including fundamental courses, KLCP and OSWP ($2.749)
- Learn Unlimited annual subscription: including access to all of OffSec courses and unlimited exam attempts ($6.099)

#### [Offensive Security Web Expert (OSWE)](https://www.offsec.com/courses/web-300/)
The OSWE covers advanced web attacks and exploitation. The certification focuses on white-box web application testing and vulnerability exploitation, where chaining multiple vulnerabilities together is needed to pass the 48 hours practical exam.
{{< figure src=/images/training-blogpost/oswe.png align=center width="30%">}}

##### Cost
The course is available in different pricing:
- Standalone course: including 1 exam attempt, including 90 days lab access ($1.749)
- Learn One annual subscription: including fundamental courses, KLCP and OSWP ($2.749)
- Learn Unlimited annual subscription: including access to all of OffSec courses and unlimited exam attempts ($6.099)

### Synacktiv
{{< figure src=/images/training-blogpost/synacktiv.png align=center width="30%" >}}
Synacktiv is a cybersecurity company founded by two IT security experts from France. It has grown into one of the established names in the field. They only recently added live/virtual trainings to their portfolio. Their onsite trainings are delivered in Paris and in French; however, their online sessions are taught in English. You can find their training schedule on their [training page](https://www.synacktiv.com/en/offers/trainings).

#### [Attacking Web Applications](https://www.synacktiv.com/en/offers/trainings/attacking-web-applications)
During this five-day training, participants will study the functioning of the security mechanisms implemented in recent web applications. The various exercises resulting from the feedback of our experts will allow them to refine their intrusion methods for the exploitation of complex vulnerabilities. Finally, learners will be able to understand the specificity of Java, PHP, Python and ASP.NET languages and frameworks, using dedicated modules.

##### Cost
€4.500* excl. VAT for 5 day training online (English) or in-person (currently only in Paris and in French)

\* cost is based on other 5 day trainings listed on their platform.

#### [Practical Web 0-Day Hunting](https://www.synacktiv.com/en/offers/trainings/practical-web-0-day-hunting)
During this five-day course, you will acquire the skills necessary to identify complex vulnerabilities within the source code of Java, PHP and .NET applications. Based on many practical cases on popular frameworks such as Spring or Symfony, participants will learn how to optimize their research using static and dynamic analysis tools. It is recommended to have a solid understanding of Web application technologies and vulnerabilities before enrolling in the course.

##### Cost
€4.500* excl. VAT for 5 day training online (English) or in-person (currently only in Paris and in French)

\* cost is based on other 5 day trainings listed on their platform.

### APISEC University
{{< figure src=/images/training-blogpost/apisec_university_logo.jpeg  align=center >}}
Training provider focusing purely on API Security, instructed by Corey J. Ball (known author of [*Hacking API's*](https://nostarch.com/hacking-apis)) . They offer multiple free API security courses on their website.

#### [API Security (ASCP)](https://www.apisecuniversity.com/courses/api-penetration-testing)
The API penetration testing course providing hands-on training, focusing on techniques to identify and address API specific vulnerabilities. The exam consists of 2 API-driven applications which have to be exploited and reported.
{{< figure src=/images/training-blogpost/ascp.png align=center width="30%">}}

##### Cost
Course material is free, The exam costs $450 + 1 free retake

### Agarri.fr
#### [Mastering Burp Suite 100% Hands-on](https://hackademy.agarri.fr/)
This training is offered by Nicolas Grégoire, an official Burp Suite Pro trainer. He will teach you how to master Burp Suite Pro in in-person or online training format training for 4 consecutive days. The training is regularly scheduled at security conferences and by Nicolas himself. It's offered in French and English. This training does not include a certification exam.
{{< figure src=/images/training-blogpost/master-burpsuite-100_hands-on.png align=center width="50%">}}

##### Cost
The training pack normally costs €3.133. However, they regularly offer early bird discounts.
Private training options are also available.

### Overview

| Training Name                                                     | Certification Name                                 | Vendor            | Training Format                | Certification                                                | Level                      | Cost (excl. VAT) | Info                                                                          | Link                                                                                                       |
| ----------------------------------------------------------------- | -------------------------------------------------- | ----------------- | ------------------------------ | ------------------------------------------------------------ | -------------------------- | ---------------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| PortSwigger Academy                                               | Burp Suite Certiied Practitioner (BSCP)            | Portswigger       | Online Labs                    | Proctored exam, 4 hours, Hands-on Lab                        | Intermediate               | Free, Exam: $90  | Course and labs are free, Exam attempt cost $90                               | [Course Link](https://portswigger.net/web-security)                                                        |
| Web Penetration Tester Job-Role Path                              | HTB Certified Web Exploitation Specialist (CWES)   | Hack The Box      | On-Demand course, Labs         | Non-proctored exam, 7 days, Hands-on Lab + report            | Entry-Level / Intermediate | €410             | Annual subscription, 1 exam attempt + retake, 100% course completion required | [Course Link](https://academy.hackthebox.com/preview/certifications/htb-certified-bug-bounty-hunter/)      |
| Senior Web Penetration Tester Job-Role Path                       | HTB Certified Web Exploitatin Expert (CWEE)        | Hack The Box      | On-Demand course, Labs         | Non-proctored exam, 10 days, Hands-on Lab + report           | Expert                     | €1.055           | Annual subscription, 1 exam attempt + retake, 100% course completion required | [Course Link](https://academy.hackthebox.com/preview/certifications/htb-certified-web-exploitation-expert) |
| Web Application Penetration Testing Professional Learning Path    | Web Application Penetration Tester (eWPT)          | INE Security      | On-Demand course, videos, labs | Non-proctored exam, 10 hours, Multiple choice, Hands-on Lab  | Entry-level                | $599             | 3 Month access 1 exam attempt + retake                                        | [Course Link](https://security.ine.com/certifications/ewpt-certification/)                                 |
| Advanced Web Application Penetration Testing                      | Web Application Penetration Tester eXtreme (eWPTX) | INE Security      | On-Demand course, videos, labs | Non-proctored exam, 7 days (+ 7 days), Hands-on Lab + report | Intermediate               | $599             | 3 Month access 1 exam attempt + retake                                        | [Course Link](https://security.ine.com/certifications/ewptx-certification/)                                |
| WEB-200: Foundational Web Application Assessments with Kali Linux | OffSec Web Assessor (OSWA)                         | OffSec            | On-Demand course, Labs         | Proctored exam, 24 hours (+24 hours), Hands-On Lab + report  | Intermediate               | $1.749           | 3 month lab access 1 exam attempt                                             | [Course Link](https://www.offsec.com/courses/web-200/)                                                     |
| WEB-300: Advanced Web Attacks and Exploitation                    | OffSec Web Expert (OSWE)                           | OffSec            | On-Demand course, Labs         | Proctored exam, 48 hours (+24 hours), Hands-On Lab + report  | Expert                     | $1.749           | 3 month lab access 1 exam attempt                                             | [Course Link](https://www.offsec.com/courses/web-300/)                                                     |
| Attacking Web Applications                                        | X                                                  | Synacktiv         | Live in-person/virtual         | No                                                           | Intermediate               | €4.500           | 5 day in-person (French) or virtual course (English)                          | [Course Link](https://www.synacktiv.com/en/offers/trainings/attacking-web-applications)                    |
| Practical Web 0-day hunting                                       | X                                                  | Synacktiv         | Live in-person/virtual         | No                                                           | Intermediate / Expert      | €4.500           | 5 day in-person (French) or virtual course (English)                          | [Course Link](https://www.synacktiv.com/en/offers/trainings/practical-web-0-day-hunting)                   |
| API Penetration Testing Course                                    | API Security Certified Professional                | APISEC University | On-Demand course, Labs         | Non-proctored exam, 12 hours, Hands-on Lab                   | Intermediate               | Free, Exam $450  | Course is Free, $450 Exam attempt + 1 free retake                             | [Course Link](https://www.apisecuniversity.com/courses/api-security-certified-professional-exam)           |
| Mastering Burp Suite Pro                                          | X                                                  | Agarri.fr         | Live in-person/virtual         | No                                                           | Intermediate / Expert      | €3.133           | 4 day in-person or virtual course                                             | [Course Link](https://hackademy.agarri.fr/)                                                                |


## Mobile Pentesting
These trainings are ideal for pentesters or developers who want to expand into mobile security testing. The resources in this section will help you understand common vulnerabilities, mobile-specific attack surfaces, and secure development practices.

### INE Security
{{< figure src=/images/training-blogpost/inesecurity_logo.jpeg align=center width="30%" >}}
The INE security training curriculum currently holds one mobile penetration testing course / certification.

#### [Mobile Application Penetration Tester (eMAPT)](https://security.ine.com/certifications/emapt-certification/)
INE recently revamped their mobile security certification. The training now covers both Android and iOS platforms, whereas their previous course focused only on Android. The curriculum takes you from the fundamentals of how mobile applications work through to exploiting common vulnerabilities in mobile environments. The exam has shifted to a multiple-choice format with a hands-on lab.
{{< figure src=/images/training-blogpost/eMAPT.png align=center width="30%" >}}

#### Cost
$599 for 3 months of premium pass* access + 1 exam attempt + 1 free retake. Afterwards, it's $749 for the Premium pass annually. 
The premium pass gives access to INE's entire content library.

### Mobile Hacking Lab
{{< figure src=/images/training-blogpost/mobile-hacking-lab.png align=center width="30%" >}}
Unlock the world of mobile security with Mobile Hacking Lab' comprehensive mobile hacking courses, available online, including free options for beginners. Their curriculum is designed to offer practical, hands-on experience in mobile security, preparing you for real-world challenges. Whether you're starting or advancing your skills, our courses provide the tools you need to succeed in the fast-evolving digital landscape. They offer exclusively mobile trainings, and you can find their full catalog on their [courses page](https://www.mobilehackinglab.com/link/K8xHa1).

#### [Certified Android Penetration Tester (CAPT)](https://www.mobilehackinglab.com/course/free-android-application-security-course)
A completely free, self-paced training designed to help you become a Certified Android Penetration Tester (CAPT). The course covers core aspects of Android app security and gives you the option to take the CAPT exam upon completion.
You can purchase additional labs to enhance and complement the learning environment.
{{< figure src=/images/training-blogpost/mhl-capt.png align=center width="50%" >}}

##### Cost
The course content is free. 
[Basic Lab](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%3Fcourseid%3Dbasic-labs) subscription costs 20€/month.
The certification attempt costs €229.

#### [Certified iOS Penetration Tester (CIPT)](https://www.mobilehackinglab.com/course/free-ios-application-security-course)
A completely free, self-paced training designed to guide learners toward becoming a Certified iOS Penetration Tester (CIPT). The course covers the essentials of iOS application security through practical lessons and assignments. After completing the training, you can take the CIPT exam to earn certification. You can purchase additional labs to enhance and complement the learning environment.
{{< figure src=/images/training-blogpost/mhl-cipt.png align=center width="50%" >}}

##### Cost
The course content is free. 
[Basic Lab](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%3Fcourseid%3Dbasic-labs) subscription costs 20€/month.
The certification attempt costs €229.

#### [Android Userland Fuzzing & Exploitation](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%3Fcourseid%3Dandroid-userland-fuzzing-and-exploitation-90-days-lab-and-exam)
This hands-on course teaches ARM/arm64 basics, Android native reverse-engineering, how to identify functions and build fuzzing harnesses (including structure-aware/libprotobuf fuzzing), crash analysis and exploit development, covering modern memory-corruption types and mitigation bypasses like ASLR and NX. The course includes an exam + certification.

##### Cost
The Training is available in 3 formulas:
- €1.428 for 30 day lab access + life time access to course material + 1 exam attempt
- €1.760 for 60 day lab access + life time access to course material + 1 exam attempt
- €2.074 for 90 day lab access + life time access to course material + 1 exam attempt

#### [Android Kernel Fuzzing & Exploitation](https://www.mobilehackinglab.com/course/android-kernel-fuzzing-and-exploitation)
This hands-on course teaches Android kernel fundamentals (building and emulating a kernel, memory management, allocators and drivers), kernel driver development, fuzzing techniques and how to build full-chain exploits for real CVEs. 
At the moment of writing this post, the course is in limited pre-sale and includes unlimited lab time until all course videos are fully live.

##### Cost
The course comes with 90 days lab access + life time access to course material + 1 exam attempt for €2.500.

### Synacktiv
{{< figure src=/images/training-blogpost/synacktiv.png align=center width="30%" >}}
The Synacktiv training catalog currently features one offensive mobile penetration testing course.

#### [Attacking Android Applications](https://www.synacktiv.com/en/offers/trainings/attacking-android-applications)
Discover methodologies and techniques for analyzing Android applications. You will study architecture, entry points, static and dynamic analysis, and master Android pentesting methodologies. This course is targeted for entry-level mobile pentesters.

##### Cost
The cost of their 2 day training offerings is not posted on their website. It's €4.500* excl. VAT for 5 day training online (English) or in-person (currently only in Paris and in French)

### SANS
{{< figure src=/images/training-blogpost/Sans-logo.png align=center >}}
The most elite training provider when it comes down to security trainings, however also the most expensive (by far). They offer a wide security training curriculum, from theoretical to very hands-on trainings. Always taught live in-person all over the world. Although their trainings are very expensive, they do offer student/facilitator programs which you can apply for to enter the training at a more affordable price, but still pricy. They have some of the best instructors at their disposal. If you ever have the opportunity to do a SANS course, by having your employer pay for it, it can be worth it.

#### [SEC575 GIAC Mobile Device Security Analyst (GMOB)](https://www.sans.org/cyber-security-courses/ios-android-application-security-analysis-penetration-testing/)
One of the coolest SANS courses is authored and instructed by my former colleague [Jeroen Beckers](https://be.linkedin.com/in/beckersjeroen), who is also a co-author of the [OWASP MASVS](https://github.com/OWASP/owasp-masvs). It focuses on both iOS and Android platforms. This could be the best mobile security course out there.
{{< figure src=/images/training-blogpost/GMOB.png align=center width="30%">}}

##### Cost
The in-person training costs €8.230 + €905 for the on-demand bundle. (or $8.780 + $999) Totaling **€9.135** (or **$9.779**) (excl. VAT).

The OnDemand bundle grants 4 months access and costs **$8.780** (excl. VAT)

The exam costs **$999** (excl. VAT).

### Overview

| Training Name                                                                 | Certification Name                                         | Vendor             | Training Format                                       | Certification                                               | Level                      | Cost                           | Info                                                           | Link                                                                                                                                                                                                                                              |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------------ | ----------------------------------------------------- | ----------------------------------------------------------- | -------------------------- | ------------------------------ | -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| The Mobile Application Penetration Testing Professional path                  | INE Security Mobile Application Penetratoin Tester (eMAPT) | INE Security       | On-Demand course, Labs                                | Non-proctored exam, 7 days (+7 days), Hands-on Lab + report | Entry-Level / Intermediate | $599                           | 3 Month access 1 exam attempt + retake                         | [Course Link](https://security.ine.com/certifications/emapt-certification/)                                                                                                                                                                       |
| Android Application Security Course                                           | Certified Android Penetration Tester (CAPT)                | Mobile Hacking Lab | On-Demand course, Labs                                | Non-proctored exam, 72 hours, Hands-on Lab + report         | Intermediate               | Course: free, Exam: €229       | Labs can be acquired separately as of 20€/month                | [Course Link](https://www.mobilehackinglab.com/course/free-android-application-security-course) <br> [Certification Link](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%2Fandroid-appsec-exam) |
| iOS Application Security                                                      | Certified iOS Penetration Tester (CIPT)                    | Mobile Hacking Lab | On-Demand course, Labs                                | Non-proctored exam, 72 hours, Hands-on Lab + report         | Intermediate               | Course: free, Exam: €229       | Labs can be acquired separately as of 20€/month                | [Course Link](https://www.mobilehackinglab.com/course/free-ios-application-security-course) <br> [Certification Link](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%2Fios-appsec-exam)         |
| Android Userland Fuzzing & Exploitation                                       | Certified Android Exploit Developer (CAED)                 | Mobile Hacking Lab | On-Demand course, Labs, also available live in-person | Non-proctored exam, 72 hours, Hands-on Lab                  | Intermediate / Expert      | €1.428 - €2.074                | Lifetime course access + 30-90 days lab access                 | [Course Link](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%3Fcourseid%3Dandroid-userland-fuzzing-and-exploitation-90-days-lab-and-exam)                                                       |
| Android Kernel Fuzzing & Exploitation                                         | Certified Android Security Researcher (CASR)               | Mobile Hacking Lab | On-Demand course, Labs, also available live in-person | Non-proctored exam, 72 hours, Hands-on Lab                  | Expert                     | €2.500                         | Lifetime course access, Labs currently free                    | [Course Link](https://www.mobilehackinglab.com/link/K8xHa1?url=https%3A%2F%2Fwww.mobilehackinglab.com%2Fcourse%2Fandroid-kernel-fuzzing-and-exploitation)                                                                                         |
| Attacking Android Applications                                                | X                                                          | Synacktiv          | Live in-person/virtual                                | No                                                          | Entry-Level                | €4.500                         | 4 day in-person (French) or virtual course (English)           | [Course Link](https://www.synacktiv.com/en/offers/trainings/attacking-android-applications)                                                                                                                                                       |
| SEC575: iOS and Android Application Security Analysis and Penetration Testing | GIAC Mobile Device Security Analyst (GMOB)                 | SANS               | Live in-person/virtual                                | Proctored exam, 2 hours, multiple choice                    | Expert                     | €9.135 or $9.779 + $999 (exam) | 6 day in-person or virtual training + 4 Months OnDemand bundle | [Course Link](https://www.sans.org/cyber-security-courses/ios-android-application-security-analysis-penetration-testing/ <br> [Certification Link](https://www.giac.org/certifications/mobile-device-security-analyst-gmob/)                      |


## Footnote
The trainings listed here are based on publicly available information as of October 2025, and prices or details may change over time.

If you know of other web, API, or mobile security trainings that deserve a mention, feel free to reach out. I’d love to include them in future updates or upcoming parts of the series.

### Additional Resources
- Security Certification Roadmap - Paul Jerimy: https://pauljerimy.com/security-certification-roadmap/
- Synack Pathways: https://www.synack.com/red-team/pathways/
- Unlocking the power of Red Teaming: An overview of trainings and certifications - Steffen Rogge: https://blog.nviso.eu/2023/07/31/unlocking-the-power-of-red-teaming-an-overview-of-trainings-and-certifications/
