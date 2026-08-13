# Security-Awareness-Program-Proposal

## A Proposal to Build Ongoing Security Awareness for a Growing Organization and Its Cloud WMS Migration
### Prepared for management review  |  July 21, 2026

# Executive Summary

IT currently carries the full weight of maintaining our security posture, configuring controls, managing access, and responding to issues, without a dedicated cybersecurity function and without a formal channel for employees to understand or reinforce that work. Two trends are converging to make that gap more costly: Transnational (TF) is growing, which means a growing number of end users with system access and a widening attack surface; and we are preparing to migrate our on-premise WMS to a cloud-based platform, where authentication, data access, and account security will depend on internet-facing controls in a way they never did before.

This proposal is not a parallel effort to IT,  it is designed to support and extend it. A Security Awareness Program gives the 20 employees with computer access at our Suffolk, VA location the context and habits to think and act with a security mindset that protects the organization, and to cooperate effectively with the security controls IT  team already puts in place rather than working around them. Where IT builds and maintains the guardrails, this program builds the understanding and everyday behavior that make those guardrails effective: reducing avoidable incidents, support tickets, and risk exposure IT would otherwise have to absorb alone now and as the company continues to add users.

The program requires only a couple of dollars per session for snacks to encourage attendance, minimal time investment (10–15 minutes monthly), and no new headcount. It uses in-house expertise already being developed toward a cybersecurity specialization. The ask is simple: approval to run it, a recurring 10-15 minute slot, and light sponsorship so employees understand it's a supported initiative.

# Why This Matters Now

Several factors make this the right moment to invest in security awareness:
* The company is growing. Every new hire with system access widens our attack surface and adds another person who needs to understand how to work securely. Building the awareness habit now, while we're at 20 users, is far easier than retrofitting it once the organization is larger.
* Cloud migration increases exposure. Moving the WMS off-premise means authentication, data access, and account security now depend on internet-facing controls (MFA, strong passwords) rather than a closed network.
* Migrations are prime phishing bait. Attackers commonly exploit system-change periods with "your account has changed, verify here" emails, timed right when employees expect something new.
*	Attacks are getting more sophisticated and faster. AI-generated phishing emails, deepfake voice and video, and automated social engineering are eliminating the obvious red flags (poor grammar, generic greetings) that employees have historically relied on to spot a scam. The end users who serve as our first line of defense need updated instincts to match this shift, recognizing attacks that no longer look the way "phishing" used to.
* 	Employees don't understand the “WHY” behind IT's controls. Security measures IT has already put in place (password requirements, DUO, WatchGuard… ) are often followed inconsistently or attempts to work around because the reasoning behind them was never explained. Awareness training closes that gap, turning compliance from an obligation into an understood practice.
  
# Observed Gaps

Day-to-day observation surfaces the following gaps. These reflect the absence of a structured awareness program -not individual fault - and are exactly what this proposal is designed to address:
* Same password format used across employees
* Screens left unlocked for long periods, including at the end of shift
* Sticky notes with credentials left on monitors
* USB drives left out and accessible
* External drives and personal mobile devices connected to company laptops without caution
* No frequent phishing simulation campaigns to test and reinforce awareness
* No consistent, informal channel for reporting something that looks suspicious
* No formal end-user education on security exists today
  
# Proposed Program

## Format

* Monthly, 10-15 minute sessions : short enough to sustain, focused enough to retain
* One topic per session, delivered consistently: a short talk, one real-world example, one clear action item
* Supported by a simple one-page reference employees can keep at their desk
* Delivered in-person, fit into an existing recurring meeting where possible
  
## 12 months Topic Roadmap
Topics are sequenced so the first several months directly support the WMS migration, then broaden into general security hygiene.


|Month	| Topic                  	| Why It Matters Now               |
-----------------------------------------------------------------------
1	      |Kickoff: Why Security Matters Here	|Frames the program and connects it to the WMS cloud migration
2	      |Passwords & Password Managers	  | Foundation for every other control
3	Multi-Factor Authentication (MFA)	Required for security hardness 
4	Phishing Recognition	Highest-risk period during and after migration rollout
5	Safe Link & Attachment Habits	Reinforces phishing training with practical habits
6	Physical & Workstation Security	Shared terminals, unlocked screens on the floor
7	Data Handling in the Cloud	Where data now lives and who can access it
8	Access Basics (Least Privilege)	No shared logins, reporting role/departure changes
9	Social Engineering Beyond Email	Phone and in-person pretexting
10	Remote / Off-Site Access Habits	If applicable to any staff
11	Incident Reporting	What to do and who to tell when something looks wrong
12	Recap, Quiz & Year 2 Planning	Measures retention and resets priorities




Resources Required
Resource	Requirement
Time	~10–15 minutes per month, one recurring slot
Budget	A few dollars per session for snacks to encourage attendance; materials built and delivered in-house at no additional cost
Tools	Existing meeting space, slides or one-pagers
Owner	Adje Gbekou, Inventory Supervisor, with informal sponsorship from IT / management
Materials	Reusable slide/one-pager template, built once and updated monthly

Measuring Success
Simple, lightweight metrics keep the program accountable without adding overhead:
Metric	How It's Tracked
Attendance	Simple sign-in per session
Knowledge retention	Short before/after poll (2–3 questions) per topic
Behavior signals	Reduction in shared-login/password reset requests to IT over time
Incident awareness	Number of employees who correctly report a suspicious email/test phish
Ownership & Governance
This program will be developed and delivered by Adje Gbekou, current Inventory Supervisor at TF. Adje holds a Master's in Data Science, Google Cybersecurity Professional Certification, and is currently studying for the CompTIA Security+ certification, building cybersecurity expertise with a focus on identity and access management, incident detection and response, Governance Risks and Compliances (GRC) that are directly applicable to designing and running this program.
It is designed to sit alongside IT team, not add to its workload: materials will be created and maintained independently, requiring no additional resources from IT beyond a recurring meeting slot and visible support for attendance if possible. Over time, better-informed end users mean fewer avoidable tickets, workarounds, and incidents for IT to manage.
As the program matures, it can expand to include lightweight phishing simulation exercises and closer alignment with access-control processes being introduced alongside the new WMS.
The Ask
•	Approval to launch the program starting next month
•	A recurring 10-15 minute slot each month, ideally tied to an existing team meeting
•	Management sponsorship, a short note or verbal acknowledgment that this is a supported initiative, so employees treat it as more than a personal project.

This is a low-cost, low-risk investment with direct relevance to the upcoming WMS migration and long-term benefit as the company continues to grow.




| Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| Identity and Access Management  | <a href="https://github.com/agbekou/Azure-IAM-Lab/blob/main/README.md"> Azure IAM & Governance Lab: Implementing Zero Trust via Least Privilege</a>|
| SIEM Implementation and Log Analysis          | <a href="https://github.com/agbekou/Cloud-Based-Threat-Hunting/blob/main/README.md">Cloud-Based-Threat-Hunting </a>|
| Security Automation with Shuffle SOAR         | <a href="https://github.com/agbekou/Brute-Force-Monitoring-Automated-Detection-Engineering/blob/main/README.md">Brute-Force-Monitoring-Automated-Detection-Engineering</a>|
| Network Traffic Monitoring and Attack Detection | <a href="https://github.com/agbekou/Validating-GRC-Policies-with-Technical-Simulations/blob/main/README.md">Validating-GRC-Policies-with-Technical-Simulations</a>|
