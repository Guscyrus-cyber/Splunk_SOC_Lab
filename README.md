# Splunk SOC Lab – 3 Phase Approach
This project follows a structured three-phase approach to simulate a real-world Security Operations Center (SOC) workflow using Splunk.
Phase 1: Data Ingestion & Search
In this phase, a custom log file (test.log) is generated to simulate authentication events such as failed and successful logins. The data is uploaded into Splunk and analyzed using SPL (Search Processing Language) queries to filter events, extract fields, and identify patterns such as repeated failed login attempts and suspicious IP activity.
Phase 2: Analysis, Reporting & Detection
This phase focuses on transforming raw log data into actionable insights. Queries are saved as reports, visualized through dashboards, and used to create alerts for detecting suspicious behavior (e.g., high number of failed login attempts). This demonstrates how analysts monitor and respond to potential security incidents.
Phase 3: Data Enrichment & Advanced Use Cases
In the final phase, advanced techniques such as lookups and data enrichment are applied to enhance analysis. External data (e.g., CSV lookup tables) is used to classify IP addresses or events, improving visibility and supporting more informed security decisions.
Objective
The goal of this lab is to demonstrate how raw log data is transformed into meaningful security insights using Splunk, following a process similar to real-world SOC operations:
Data → Ingestion → Analysis → Detection → Response



