# Sentinel Health Monitoring – Ingestion Delay

Monitor and detect data ingestion delays in Microsoft Sentinel to ensure timely log availability and accurate incident detection.

## Overview

Microsoft Sentinel relies on continuous log ingestion from multiple data sources such as Microsoft Defender, Azure resources, and third-party connectors.  
In some cases, logs can be delayed or disrupted, which impacts detection, alerting, and investigations.

This repository provides **KQL queries** and **dashboards** to help you monitor ingestion delays in Sentinel and take proactive action when data sources fall behind.

---

## Features

- Detect delayed or stopped ingestion across data sources  
- Measure **end-to-end ingestion latency** for Defender and other connectors  
- Identify which connectors or tables are most impacted  
- Help SOC teams act before detection gaps appear  
- Fully KQL-based — no external dependencies

---

## Repository Structure

