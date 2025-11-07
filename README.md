SIEM Implementation (Wazuh) - Major Project Submission
Project Description
This major cybersecurity project details the end-to-end deployment, configuration, and validation of a functional Security Information and Event Management (SIEM) platform built using Wazuh (v4.14.0) and supporting infrastructure. The core purpose of the project was to create a resilient monitoring solution capable of real-time log aggregation and advanced threat correlation across virtualized systems.

The submission validates the platform’s operation through the successful detection and analysis of three critical security scenarios:
1. Log Correlation: Identifying a high-severity Brute Force attack.
2. Vulnerability Management: Detecting a critical CWE-416 flaw on the Windows endpoint.
3. Host Integrity: Monitoring for anomalies on the Manager host itself.

Architecture Overview
The project utilizes a client-server architecture hosted on VMware Workstation:
1. Manager/Server: Kali Linux VM running the Wazuh Manager, Indexer (Elasticsearch), and Dashboard.
2. Endpoint: Windows 10 VM running the Wazuh Agent for event monitoring.


