# SOC Project

## Introduction
- In today’s fast-changing cybersecurity domain, strong Security Operations Centers (SOCs) are more important than ever. As cyber threats grow more advanced, organizations must improve their detection and response to protect their data and assets.
One way to sharpen these skills is by building a fully automated SOC home lab. This project simplifies the process, showing how to set up a lab using open-source tools.

## Objective
- The SOC home lab aims to provide hands-on experience in setting up and managing a simulated Security Operations Center.
- It helps users familiarize themselves with open-source tools like Wazuh for alerts, Shuffle for SOAR, and TheHive for case management.
- The lab also offers training in incident detection, analysis, and response, while teaching integration of tools to improve efficiency.
- Also, it includes threat intelligence using services like VirusTotal to enhance the analysis of Indicators of Compromise (IOCs).

### Skills Learned
- SOC Setup and Management: Learn how to setup, confihure and operate SOC in your own environment.
- Learn Tools: Get experience with open-source tools like Wazuh, Shuffle and TheHive for alerting, automation, and case management.
- Integration: Learn how to use and integrate different tools together.
- Handling IOCs: ................


### Tools Used
- Windows 10 Virtual Machine.
- Wazuh
- Shuffle
- TheHive

## Steps
1. Visual representation of the SOC Automation Lab Workflow
  - Using <a href="https://app.diagrams.net/">draw.io</a> we are going to show how the SOC Automation Lab would run.

      ![image](https://github.com/user-attachments/assets/6426832b-9ef6-4008-bf32-f7e09dbfc1cd)

    - Event Detection: A Windows 10 client detects a suspicious activity.
    - Event Analysis: Wazhu receives and analyzes the event.
    - Alert Generation: Wazhu generates an alert if the event is deemed suspicious.
    - Alert Distribution:
    - The alert is sent to Shuffle for further processing.
    - Shuffle also sends an email notification to the SOC Analyst.
    - Case Management: Shuffle creates a case in TheHive and assigns it to the SOC Analyst.
    - Analyst Review: The SOC Analyst reviews the alert and case details.
    - Action Planning: The SOC Analyst decides on the appropriate response action.
    - Action Execution: The SOC Analyst instructs Shuffle to execute the action.
    - Action Implementation: Shuffle sends the action to Wazhu for implementation.
    - Action Completion: Wazhu performs the action to mitigate the threat.

2. 
