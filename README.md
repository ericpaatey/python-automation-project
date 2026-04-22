# DevOps Automation Toolkit (Python)

A collection of Python scripts designed to automate repetitive SRE/DevOps tasks, improve system reliability, and reduce operational toil.

---

## Overview

This repository provides practical automation scripts for managing and monitoring cloud infrastructure and containerized applications in AWS environments.

The goal: **Eliminate manual work, improve uptime, and enable faster incident response.**

---

## Features

### 1. Application & Container Monitoring (Auto-Recovery)
- Continuously monitors websites and containerized applications
- Supports HTTP(S) and TCP health checks
- Detects downtime in near real-time
- Sends automated email alerts
- Attempts automatic restart of services/containers/servers
- Logs events and system status

👉 **Outcome:** Reduced Mean Time To Recovery (MTTR) and improved system resilience

---

### 2. EC2 Volume Backup & Restore Automation
- Creates EBS snapshots (on-demand or scheduled)
- Supports tagging and retention strategies
- Restores snapshots into new volumes
- Enables cross-AZ recovery scenarios
- Logs all backup/restore operations

👉 **Outcome:** Improved disaster recovery and data protection

---

### 3. EC2 Health & Status Monitoring
- Monitors EC2 instance status checks:
  - System status checks
  - Instance status checks
- Detects impaired or degraded instances
- Captures lifecycle events (start/stop/reboot)
- Sends alerts for unhealthy resources
- Provides logging and reporting

👉 **Outcome:** Early detection of infrastructure issues before escalation

---

### 4. EKS Cluster Health Monitoring
- Monitors Kubernetes cluster health
- Tracks node readiness and availability
- Checks critical components:
  - API Server
  - etcd
  - CoreDNS
- Detects failed pods and workloads
- Sends alerts and logs cluster state

👉 **Outcome:** Improved reliability of container orchestration environments

---

## Architecture Highlights

- Python-based modular scripts
- AWS SDK (`boto3`) integration
- Logging (JSON / CSV)
- Email alerting (SMTP / SES compatible)
- Config-driven execution (YAML / JSON)

---

## Tech Stack

- Python 3.x
- AWS (EC2, EBS, EKS)
- boto3
- SMTP / Email Gateway
- Cron / Task Scheduler
- PyCharm (development environment)

---

## Getting Started

### Prerequisites

- Python 3.x installed
- AWS CLI configured (`aws configure`)
- IAM permissions for:
  - EC2
  - EBS
  - EKS
  - CloudWatch (optional)
- Email service credentials (for alerts)

---

### Installation

```bash
git clone https://github.com/ericpaatey/python-automation-project.git
cd python-automation-project
