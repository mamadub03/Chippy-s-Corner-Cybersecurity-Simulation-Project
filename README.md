# Chippy’s Corner Cyber Attack Simulation Lab

While preparing for my CompTIA Security+ certification, I built a home lab to move beyond theory and apply concepts in practice. The environment included Windows 10 endpoints, a domain controller, and a XAMPP web server, all intentionally configured with vulnerabilities to simulate an internal staff network for the fictitious company *Chippy’s Corner*. This setup allowed me to simulate realistic cyberattacks and apply defenses across the full security lifecycle: risk assessment, red teaming, incident response, hardening, and governance.

## Stages

### Risk Assessment
- Conducted a structured risk analysis, developed a risk register, and identified critical vulnerabilities across the environment.  
- Produced a risk report outlining threats, likelihood, and business impact.

### Red Team Engagement
- Simulated an adversary attack using an assumed breached model.  
- Executed a reverse shell, built a custom Python C2 tool for persistence, and performed data exfiltration of sensitive data after compromising vulnerable endpoints.  
- Findings were mapped to **MITRE ATT&CK** and **OWASP Top 10**.

### Incident Response
- Followed **NIST SP 800-61** to investigate and respond to the simulated attack.  
- Used Splunk + Sysmon logs to trace attacker activity.  
- Produced a full incident response report with root cause analysis, evidence, and containment steps.

### Hardening
- Applied fixes to reduce the attack surface:  
  - Enforced strict password policies  
  - Disabled unnecessary services  
  - Rebuilt the web server on a hardened baseline  
  - Minimized software footprint  
  - Strengthened firewall rules  
- Retested to validate improvements.

### Governance, Risk, and Compliance (GRC)
- Conducted a gap analysis against **NIST SP 800-53**.  
- Created security policies and developed a compliance report.  
- Documented alignment with standards to demonstrate governance and structured risk management practices.
