# Power BI Automation Kit

Automation patterns for managing Power BI datasets and workspaces using APIs and orchestration tools.

This repository demonstrates how to implement **reliable dataset refresh orchestration** integrated with data platform pipelines.

---

## Problem

In enterprise environments, dataset refreshes often fail due to:

- Manual execution
- Timing mismatches with data processing
- API rate limits
- Lack of retry strategies
- Dependency issues between pipelines and reports

---

## Solution

A structured automation approach using:

- Power BI REST API
- Logic Apps / orchestration workflows
- Service Principals
- Controlled refresh execution
- Retry and throttling handling

---

## Features

- Dataset refresh automation
- Workspace and dataset management
- Rate limit handling
- Retry strategies
- Execution logging
- Integration with Databricks pipelines

---

## Architecture Overview

Typical flow:
Databricks Processing
↓
Logic App Trigger
↓
Power BI API
↓
Dataset Refresh Monitoring


---

## Technologies

- Power BI REST API
- Azure Logic Apps
- Python
- Databricks
- Microsoft Fabric ecosystem

---

## Repository Structure

/examples → API calls and automation samples
/docs → Architecture decisions


---

## Goal

Transform Power BI refresh processes from manual operations into **automated and reliable data platform components**.
