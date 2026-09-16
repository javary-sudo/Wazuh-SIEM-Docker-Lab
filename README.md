# Centralized SIEM & Automated Threat Containment Lab

## Project Overview
This project demonstrates the architecture and deployment of an isolated, multi-node virtual infrastructure designed for real-time security telemetry monitoring and automated incident remediation. The environment serves as a practical simulation of a corporate Security Operations Center (SOC) pipeline.

## Technical Infrastructure Stack
*   **Hypervisor:** Oracle VirtualBox
*   **SIEM Platform:** Centralized Wazuh SIEM Cluster
*   **Operating Systems:** Linux Administration (Ubuntu Server target, Kali Linux attacker framework)
*   **DevOps Ecosystem:** Containerized Docker runtime environments (`root-wazuh-1`)
*   **Defensive Automation:** OSSEC host configuration mechanics and active-response rules

## Core Engineering Implementations

### 1. Centralized Log Aggregation
Architected endpoint telemetry collection channels by customizing `ossec_config` files directly on target nodes. This standardized localized lo
