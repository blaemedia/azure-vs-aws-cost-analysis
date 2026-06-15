# AWS Cost Breakdown – Small Web Application

## 1. Application Specification
This project evaluates the cost of hosting a small web application on AWS.

### Resources:
- 1 vCPU, 2 GB RAM (Linux EC2 instance)
- 50 GB EBS storage
- 20 GB S3 storage
- 100 GB monthly outbound data transfer
- Always running (24/7)

---

## 2. AWS Services Used
- Amazon EC2 (compute)
- Amazon EBS (block storage)
- Amazon S3 (object storage)
- Data Transfer Out to Internet

---

## 3. Monthly Cost Estimate

| Component | Service | Estimated Cost |
|----------|--------|----------------|
| Compute | EC2 t3.small | $18.00 |
| Storage | EBS 50 GB | $4.00 |
| Object Storage | S3 20 GB | $0.50 |
| Data Transfer | 100 GB | $9.00 |

### Total AWS Monthly Cost: **$31.50**

---

## 4. Summary
AWS provides relatively low-cost Linux hosting for small workloads. Compute is the largest cost driver, followed by network egress.