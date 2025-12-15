About Me

Hello! I’m Philippine Marine Major General Eric E. Nicanor (Retired) — a cybersecurity and technology operations executive with 37 years of experience leading national defense programs in military operations, ICT, C4ISR systems, weapons systems, and cybersecurity strategy.

Now fully engaged in the field of cybersecurity, I am building on my operational leadership background to continue my passion on IT/cyber operations, SOC operations, and cyber resilience. This portfolio documents my journey as I bridge executive leadership with hands-on technical capabilities in the evolving landscape of information security.

🔍 Interests

Security Operations Center (SOC) management and leadership
Threat detection, blue team workflows, and incident response
Ethical Hacking
Vulnerability Assestment
Penetration Testing
Cybersecurity governance and compliance (NIST, ISO, CIS)
Cyber resilience at national, enterprise, and operational levels
Strategic technology transformation and IT systems leadership

🎓 Certifications & Training

Certified Ethical Hacker (CEH)
Certified Information Systems Security Officer (CISSO)
Vulnerability Assessment & Penetration Testing (VAPT) – GUIDEM
Cyber Defense & Threat Hunting (CDTH) – GUIDEM
Microsoft Cybersecurity Analyst – Coursera
Elastic SIEM (Elastic.co)
CompTIA CySA+ (Udemy)

🌱 Why I’m Sharing This

This portfolio is more than a résumé — it's a living journal of my growth in cybersecurity and a message to others that it's never too late or too early to build your path in this field.

I've developed much of my knowledge through a mix of free, affordable, and mission-aligned resources, including:

Open-source labs using Elastic, Wazuh, MITRE ATT&CK, and Kali Linux
Online learning via Coursera, Udemy, and TryHackMe
Real--world training through GUIDEM, whose CDTH and VAPT programs gave me hands-on exposure to cyber defense, threat detection, and SOC practices
I share this openly to encourage:

Veterans and professionals considering a career shift into cybersecurity
Career changers coming from non-technical or leadership backgrounds
Young students and early-career learners who want to start strong with discipline and curiosity — even without expensive tools
If this portfolio inspires just one person to take the next step in their journey, it has already served its purpose.

REFLECTIONS ....
Open to meaningful conversations in cybersecurity leadership, IT development, and strategic & tactical cyber

 1. Proactive Threat Hunting: The Case of the Compromised Infrastructure Console (A Reflection)
  
  ​Almost a year ago, I managed a critical incident as a freelance consultant that remains one of my most instructive lessons in cyber defense. It’s a classic case    study of why proactive threat hunting is essential when defending high-value infrastructure hastily deployed with vendor systems.
  
  ​The Anomaly:
  During continuous monitoring of an event network, I noticed something unusual: the LED wall management console was generating persistent, high-volume outbound      ICMP traffic to a foreign IP address. ICMP is rarely used this way—so why the persistence?
  
  ​The Deep Dive:
  My XDR agent didn’t raise a high-confidence alert, but I trusted my instincts. I ran targeted XQL queries, assisted by generative AI tools to accelerate query      building. The results confirmed unsigned parent-child processes driving ICMP traffic—highly abnormal for a display console. OSINT checks revealed links to known    APT tactics. This wasn’t commodity malware; it was a sophisticated adversary establishing long-term persistence.
  
  ​The Response:
  • ​Bridging the Gap: Used XDR Live Insights to confirm the process identity and connection.
  • ​Intelligence Correlation: Validated the file hash against external threat intel, confirming APT associations.
  • ​Evasion & Kill: The malware dynamically shifted registry keys to evade detection. I hunted the new process and executed a priority kill, followed by artifact     removal.
  • ​Verification: Remote terminal cheks confirmed the C2 link was severed.
  
  ​The Takeaway:
  You cannot wait for the alert—you must hunt for the threat. Advanced adversaries are leveraging ICMP-based C2 channels, dynamic evasion, and supply-chain blind     spots to bypass automated controls.
  ​For security teams, the lessons are clear:
  • ​Proactive sweeps for unusual outbound traffic on vendor-controlled infrastructure.
  • ​Integrated remediation that balances security with system availability.
  • ​AI as a force multiplier—accelerating query generation, correlation, and live response.
  
  ​This reflection underscores a simple truth: Tools don't defend, people do. Threat hunting is not optional; it is the decisive edge against state-level               adversaries.
