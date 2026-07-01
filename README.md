# Azure Cloud Mastery - Day 1

## Manual Foundation Network Deployment
For Day 1, I manually built out the foundational core network infrastructure directly inside the Azure Portal to establish isolated environments for future production workloads.

### Completed Infrastructure:
* **Resource Group**: `rg-cloudmastery-day1` (Deployed in Germany West Central)
* **Virtual Network (VNet)**: Core backbone network configuration
* **Subnets**: Isolated networking components for secure resource segregation

### Proof of Work
<img width="1247" height="602" alt="image" src="https://github.com/user-attachments/assets/67a4c291-23e8-41d9-bb0f-c95b9980252d" />

---

## Day 2: Infrastructure as Code Foundation & Provider Initialization

### Objective
Transitioning from manual portal configurations to programmatic infrastructure. Today, I initialized the Terraform workflow by defining version constraints and configuring the Microsoft Azure API provider wrapper.

### Core Concepts Mastered
* **Provider Ecosystem**: Understanding how HashiCorp plugins translate HCL into Azure API calls.
* **Version Locking**: Implementation of semantic version pinning (`~> 3.0`) to safeguard automation code against breaking upstream API changes.

### Architectural Artifacts
* Created `providers.tf` containing the declarative block for backend communication.
