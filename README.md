# Azure Landing Zone Architecture — Interactive Traffic Flow

An interactive visualization of a secure Microsoft Azure Landing Zone architecture, demonstrating hub-and-spoke networking, centralized security, private connectivity, and cloud monitoring.

🔗 **Live Demo:** https://moukhtiar.github.io/azure-landing-zone-architecture/

## Overview

This project visualizes how network traffic flows through an enterprise-style Azure Landing Zone, from internet ingress to application workloads and private Azure PaaS services.

The interactive diagram includes animated traffic packets, step-by-step walkthroughs, traffic scenario selection, and explanations of key architecture components.

## Architecture Components

* **Network Security:** Azure DDoS Protection, Azure Firewall, Network Security Groups (NSGs).
* **Application Security:** Azure Application Gateway with Web Application Firewall (WAF).
* **Hub-and-Spoke Networking:** Centralized connectivity and workload network isolation.
* **Private Connectivity:** Azure Private Endpoints for SQL Database, Storage Account, and Key Vault.
* **Monitoring and Detection:** Azure Monitor, Log Analytics, Microsoft Sentinel, and Microsoft Defender for Cloud.
* **Governance and Identity:** Microsoft Entra ID, Azure Policy, RBAC, and cost management.

## Interactive Features

* ▶ Animated traffic-flow visualization.
* 🔄 Play, pause, and replay controls.
* ➡ Step-by-step traffic walkthrough.
* 🎯 Automatic component highlighting.
* 🔐 Private endpoint connectivity scenarios.
* 📊 Explanations of security controls and network flows.

## Example Traffic Flows

1. **Inbound:** Internet → DDoS Protection → Azure Firewall → Application Gateway/WAF → Application Tier.
2. **Private Data Access:** Application Tier → Private Endpoint → Azure SQL Database.
3. **Private Storage Access:** Application Tier → Private Endpoint → Azure Storage.
4. **Secrets Management:** Application Tier → Private Endpoint → Azure Key Vault.
5. **Security Monitoring:** Application and platform diagnostics → Azure Monitor → Log Analytics / Microsoft Sentinel.

## Design Principles

The architecture is intended to support enterprise cloud design practices aligned with the Microsoft Cloud Adoption Framework (CAF), Azure Well-Architected Framework, Zero Trust, and Microsoft Cloud Security Benchmark.

Key considerations include network segmentation, least-privilege access, centralized security controls, private service connectivity, monitoring, and governance.