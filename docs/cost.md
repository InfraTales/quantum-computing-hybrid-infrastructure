# Cost Analysis (₹)

Cost estimates for **Quantum Computing Infrastructure** in **Indian Rupees (₹)**.

## AWS Braket Pricing

| Quantum Device | Cost per Task (₹) | Notes |
|---------------|-------------------|-------|
| **Simulator (SV1)** | ₹400/min | State vector |
| **Simulator (TN1)** | ₹600/min | Tensor network |
| **IonQ** | ₹2,500/task + ₹25/shot | Trapped ion |
| **Rigetti** | ₹2,500/task + ₹3/shot | Superconducting |
| **D-Wave** | ₹18,000/min | Quantum annealing |

## Typical Monthly Costs

| Use Case | Monthly Cost (₹) | Notes |
|----------|------------------|-------|
| Research/Dev | ₹50,000–100,000 | Simulator-heavy |
| Hybrid workloads | ₹150,000–300,000 | Mix of devices |
| Production | ₹300,000–600,000 | Real QPU usage |

## Classical Compute

| Service | Monthly Cost (₹) |
|---------|------------------|
| EC2 (classical) | ₹20,000–50,000 |
| S3 (results) | ₹2,000–5,000 |
| Lambda | ₹3,000–8,000 |

## Cost Optimization

- **Use simulators** – For algorithm development
- **Batch jobs** – Combine multiple circuits
- **Shot optimization** – Minimize shots needed
- **Hybrid approach** – Classical preprocessing
