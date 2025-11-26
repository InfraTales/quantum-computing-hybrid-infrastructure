# Runbook

## Deployment

```bash
terraform init && terraform apply -var="environment=prod"
```

## Running Quantum Jobs

```python
from braket.aws import AwsDevice
from braket.circuits import Circuit

# Create circuit
circuit = Circuit().h(0).cnot(0, 1)

# Run on simulator
device = AwsDevice("arn:aws:braket:::device/quantum-simulator/amazon/sv1")
task = device.run(circuit, shots=1000)
result = task.result()
```

## Hybrid Workflow

1. Classical preprocessing
2. Quantum circuit execution
3. Classical postprocessing
4. Iterate until convergence

## Monitoring

- Track job costs daily
- Monitor queue times
- Review result quality
- Optimize shot counts
