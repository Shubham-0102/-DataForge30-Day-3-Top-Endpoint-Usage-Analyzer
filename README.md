# DataForge30 – Day 3: Top Endpoint Usage Analyzer

## Project Overview
This is **Day 3** of the **DataForge30 challenge**, where I build **one real-world data project per day**.

In this project, I analyzed server access logs to identify **which API endpoints/pages are used the most**. This type of analysis is commonly used by backend and data engineering teams to understand traffic patterns and optimize systems.

---

## Objective
- Read server access logs
- Extract endpoint information
- Count endpoint usage frequency
- Generate a simple analytics report

---

## Tech Stack
- Python
- Pandas
- Google Colab

---

## Input
- `access.log`  
  A simplified server log containing:
  - IP address
  - HTTP method
  - Endpoint
  - Status code

---

## Output
- `day3_top_endpoints.txt`  
  A text report showing how many times each endpoint was accessed.

Example:
