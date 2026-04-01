🔍 Risk Monitoring & Threat Detection (PRTG + IoCs)

## 📌 Overview
I designed a proactive monitoring strategy using Paessler PRTG to detect potential threats across critical business systems, including an SQL database, Linux development environment, and IIS web server.

## ⚙️ Problem
I wanted to address how organizations can detect threats early across key systems, since lack of monitoring can lead to data breaches, operational disruptions, and loss of sensitive information.

## ⚙️ Approach
- I identified critical assets (SQL database, Linux system, IIS web server)  
- I selected appropriate sensors in PRTG to monitor system activity  
- I mapped each sensor to relevant Indicators of Compromise (IoCs)  
- I defined alert thresholds based on expected system behavior  
- I prioritized systems based on data sensitivity and business impact  
- I aligned monitoring strategy with security best practices   

## 📊 Key Decisions
- **Asset prioritization:** I focused on systems handling proprietary and financial data to reduce highest risk exposure  
- **IoC mapping:** I linked each sensor to known attack behaviors (e.g., brute force, data exfiltration, privilege escalation)  
- **Threshold design:** I defined high/low thresholds to balance detection accuracy and reduce false positives  

## 🎯 Results
- I created a structured monitoring strategy across multiple systems  
- I identified key indicators of compromise tied to real-world attack patterns  
- I demonstrated how sensor-based monitoring can support early threat detection and system protection  

## Detection & Response Scenario  

## ❗ Detection & Response Scenario
If suspicious activity were detected, I would:

1. **Validate the alert**
   - Confirm abnormal sensor activity (e.g., unusual queries, login attempts, bandwidth spikes)  
   - Compare against baseline behavior  

2. **Investigate the source**
   - Identify affected systems and entry points  
   - Analyze logs for patterns (e.g., brute force, unauthorized access)  

3. **Escalate if necessary**
   - Notify appropriate stakeholders based on severity  
   - Document findings and potential impact  

4. **Containment actions**
   - Block suspicious activity (IPs, sessions, or processes)  
   - Isolate affected systems if needed   

## 🖼️ Example Outputs
* screenshots*

## 📚 Impact
- I demonstrated how proactive monitoring supports threat detection and risk reduction  
- I improved visibility into system activity across critical assets  
- I aligned monitoring practices with real-world security frameworks (NIST, MITRE ATT&CK)   

## 📚 Next Steps
- I would integrate monitoring into a SIEM platform for centralized analysis  
- I would automate alert correlation and response  
- I would expand detection coverage with additional sensors (e.g., privilege escalation monitoring, WAF integration)  
