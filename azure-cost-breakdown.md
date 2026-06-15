# Azure Cost Breakdown – Small Web Application

## 1. Application Specification
Same workload as AWS for fair comparison.

### Resources:
- 1 vCPU, 2 GB RAM (Linux VM)
- 50 GB Managed Disk
- 20 GB Blob Storage
- 100 GB monthly outbound data transfer

---

## 2. Azure Services Used
- Azure Virtual Machines
- Azure Managed Disks
- Azure Blob Storage
- Bandwidth (Data Transfer)

---

## 3. Monthly Cost Estimate

| Component | Service | Estimated Cost |
|----------|--------|----------------|
| Compute | B2s VM (Linux) | $24.00 |
| Storage | Managed Disk 50 GB | $5.00 |
| Object Storage | Blob Storage 20 GB | $0.50 |
| Data Transfer | 100 GB | $10.00 |

### Total Azure Monthly Cost: **$39.50**

---

## 4. Summary
Azure is slightly more expensive for Linux workloads at small scale, mainly due to compute pricing, but integrates well with Microsoft ecosystems.