# Security Overview

Security posture of **Quantum Computing Infrastructure**.

## Data Protection

- **Circuit encryption**: TLS in transit
- **Results encryption**: S3 SSE-KMS
- **Job isolation**: Per-customer queues
- **No data persistence**: On quantum devices

## Access Controls

- **IAM policies**: Braket permissions
- **Job quotas**: Prevent runaway costs
- **VPC endpoints**: Private API access
- **Audit logging**: CloudTrail integration

## Quantum-Specific Security

- **Algorithm IP**: Circuits not stored on devices
- **Result privacy**: Encrypted storage
- **Device access**: Shared infrastructure model

## Compliance

- SOC 2 (AWS Braket)
- Research data governance
- Export controls awareness

> See `SECURITY.md` for detailed configurations.
