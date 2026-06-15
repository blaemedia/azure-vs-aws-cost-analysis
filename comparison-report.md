# AWS vs Azure Cost Comparison Report

## 1. Objective
This report compares the monthly cost of hosting a small web application on AWS and Azure using equivalent infrastructure.

---

## 2. Application Assumptions
- 1 vCPU, 2 GB RAM
- 50 GB storage
- 100 GB monthly outbound traffic
- 24/7 uptime

---

## 3. Cost Comparison

| Provider | Monthly Cost |
|----------|-------------|
| AWS | $31.50 |
| Azure | $39.50 |

---

## 4. Key Findings

- AWS is approximately 20–25% cheaper for this small Linux-based workload.
- Compute (VM/EC2) is the biggest cost driver on both platforms.
- Data transfer costs are similar across providers.
- Storage costs are nearly identical.

---

## 5. Networking Impact

Both AWS and Azure charge for outbound data transfer.
This becomes a major cost factor as the application scales.

Inter-zone traffic also adds hidden costs in both ecosystems.

---

## 6. Discount Models

### AWS
- Savings Plans (1–3 years commitment)
- Reserved Instances (up to 70% discount)

### Azure
- Reserved VM Instances
- Azure Hybrid Benefit (for Windows workloads)

---

## 7. Conclusion

For a small startup running Linux-based workloads, AWS is slightly more cost-effective.
Azure becomes more competitive in enterprise environments or when using Windows-based systems and Microsoft integrations.