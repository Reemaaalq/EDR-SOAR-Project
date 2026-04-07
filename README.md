# EDR-SOAR-Project

### Objective
> This project demonstrates the integration of Endpoint Detection and Response (EDR) with Security Orchestration, Automation, and Response (SOAR) to create an automated threat detection and mitigation workflow. It simulates real-world attack scenarios, detects them using EDR rules, and triggers automated responses via SOAR playbooks
### Skills Learned
- EDR Configuration & Rule Writing Creating custom D&R rules in LimaCharlie Fine-tuning detection thresholds to reduce false positives </br>  <i> (refer to Figure 1)</i>
- SOAR Playbook Development</br>
   * Designing automated workflows in Tines <i> (refer to Figure 2)</i>
   * Integrating multiple security tools via APIs
- Incident Response Automation </br>
   * Endpoint isolation   <i> (refer to Figure 3)</i> 
   * Automated alerting and ticket creation   <i> (refer to Figure 4)</i> 
- Threat Simulation & Testing </br> 
   * Safe execution of simulated attacks for validation
-  Security Operations Center (SOC) Practices </br>
   * Event triage and escalation
   * Cross-platform security tool integration

### Tools Used
•	Design: Draw.io </br>
•	EDR: LimaCharlie </br>
•	SOAR: Tines </br>
•	Communication: Slack, Email </br>
•	Scripting: Python </br>
•	Testing: created a D&R rules to detect LaZagne (attack simulation) </br>

### Outcome
> This project showcases the ability to detect and respond to threats in real-time using automation, reducing incident response time from hours to seconds.

### screenshots
1)
<img width="1780" height="355" alt="Screenshot 2026-04-07 125908" src="https://github.com/user-attachments/assets/ca35081f-2024-4081-8a08-506ffe953396" />
<img width="1785" height="221" alt="Screenshot 2026-04-07 125945" src="https://github.com/user-attachments/assets/c4c4d3f0-52fa-43f7-aa6b-5e5ca59eea44" />
 <i> Figure 1:customized Detection and Response Rule to detect LaZagne (attack simulation)  </i> </br>
 <img width="495" height="749" alt="Screenshot 2026-04-07 131228" src="https://github.com/user-attachments/assets/78bdb291-b40f-4ef4-88cf-dd937241b489" />

2)
<img width="1135" height="856" alt="WorkFlow StoryBoard" src="https://github.com/user-attachments/assets/16bebf9e-e6ab-4e1b-8895-1905f59225d2" />
<i> Figure 2: Automation Security workflow </i></br>
3)<img width="1270" height="810" alt="image" src="https://github.com/user-attachments/assets/50b22982-8acc-43ee-819b-31cfe6899fb2" />
 <i> Figure 3: Device being isolated after user prompted to isolate.</i>
4)
   <img width="1363" height="252" alt="Screenshot 2026-04-07 131840" src="https://github.com/user-attachments/assets/4b072ecd-20db-4244-9b89-597d79cfa573" /> </br>
   <i> Figure 4: Alert being sent to Slack for Invetigation</i>

