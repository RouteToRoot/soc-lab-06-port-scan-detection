# SOC Lab 06 — Detecting Port Scanning Activity

## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Lab Objectives](#lab-objectives)
3. [Environment Overview](#environment-overview)
4. [Detection Workflow](#detection-workflow)
5. [Traffic Analysis](#traffic-analysis)
6. [Detection Engineering Insights](#detection-engineering-insights)
7. [Evidence](#evidence)
8. [Conclusions](#conclusions)
9. [Next Steps](#next-steps)

---

## Executive Summary
This lab focuses on detecting port scanning activity using network traffic analysis.

Port scanning is a common reconnaissance technique used by attackers to identify open ports and services on a target system. By analyzing packet-level data, security analysts can identify scanning behavior and detect early stages of an attack.

In this lab, network traffic is captured using Wireshark while a port scan is generated using Nmap. The captured traffic is then analyzed to identify scanning patterns such as repeated connection attempts across multiple ports.

This lab demonstrates how SOC analysts detect reconnaissance activity and analyze network traffic to identify potential threats.

## Lab Objectives
- Generate port scanning activity using Nmap  
- Capture network traffic using Wireshark  
- Identify port scanning patterns in packet data  
- Analyze SYN scan behavior  
- Understand how reconnaissance activity appears in network traffic  
- Develop foundational network detection skills  

## Environment Overview
**Operating System:** Ubuntu Linux (Virtual Machine)

**Tools Used**
- Wireshark
- Nmap

**Network Setup**
- Localhost traffic (127.0.0.1)
- Single VM environment

## Detection Workflow

### 1. Start Packet Capture in Wireshark

Wireshark is used to capture live network traffic for analysis.  
Security analysts rely on packet capture tools to observe real-time activity and detect suspicious behavior.

Open Wireshark and select the active network interface.

Start capturing traffic to begin monitoring network activity.

## Traffic Analysis

## Detection Engineering Insights

## Evidence

## Conclusions

## Next Steps
