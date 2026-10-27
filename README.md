<p align="center">
  <img src="assets/hero.png" width="100%" alt="Majed Almabadi — cybersecurity field notes. Making sense of the signals. Log analysis, threat hunting, and detection.">
</p>

<p align="center">
  <a href="#featured-investigation"><b>Featured investigation</b></a> &nbsp; / &nbsp;
  <a href="https://github.com/Majed-Almabadi?tab=repositories"><b>Repositories</b></a> &nbsp; / &nbsp;
  <a href="https://github.com/Majed-Almabadi/Detecting-SSH-Brute-Force-Attempts-with-Splunk/blob/main/Splunk_SSH_Analysis_Report.pdf"><b>Investigation report</b></a>
</p>

## From signal to evidence

I'm **Majed Almabadi**, and my current work explores cybersecurity through authentication logs, threat hunting, and detection in Splunk. I focus on connecting an observable signal to a clear finding and a repeatable search.

![Investigation approach: observe SSH telemetry, investigate sources and authentication outcomes, and build repeatable SPL detection logic](assets/investigation-flow.gif)

## Featured investigation

<a href="https://github.com/Majed-Almabadi/Detecting-SSH-Brute-Force-Attempts-with-Splunk">
  <img src="assets/case-ssh.png" width="100%" alt="SSH brute-force investigation: 2400 events reviewed, 1216 failed authentication events, and suspicious source 10.0.0.25. Open the project.">
</a>

**[SSH Authentication Log Analysis & Threat Hunting Using Splunk](https://github.com/Majed-Almabadi/Detecting-SSH-Brute-Force-Attempts-with-Splunk)**

Investigated JSON-based SSH logs, reconstructed suspicious-source activity, and documented eight SPL searches with findings and supporting screenshots. The source investigation identified **174 failed authentication attempts** and **16 successful logins** from the same suspicious IP.

`Splunk Enterprise` &nbsp; `SPL` &nbsp; `SSH` &nbsp; `JSON logs` &nbsp; `Ubuntu`

## What I'm working with

<img src="assets/toolkit.gif" width="100%" alt="Programming: Python. Linux environments: Kali Linux and Ubuntu. Network analysis and discovery: Wireshark and Nmap. Web testing and discovery: Burp Suite and Gobuster. Penetration testing: Metasploit.">

## How I approach a case

1. **Start with the data.** Confirm ingestion and understand the fields before interpreting activity.
2. **Add context.** Compare authentication outcomes, repeated attempts, and source behavior.
3. **Make the finding useful.** Document the evidence and turn the investigation into reusable detection logic.

![Less noise. More evidence. Majed — Cybersecurity.](assets/footer.png)
