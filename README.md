# Platform Catalog Repository

**Owner**: Platform Engineering Team  
**Upstream GitHub Remote**: `https://github.com/brunobml/platform-catalog.git`

This repository stores standard, hardened, and approved cloud-native API blueprints (`ResourceGraphDefinition`s) powered by **Kro (Kube Resource Orchestrator)** and **AWS Controllers for Kubernetes (ACK)**.

## Directory Structure
- `blueprints/`: Kro `ResourceGraphDefinition`s defining reusable composite APIs.
  - `message-processor-rgd.yaml`: Worker deployment + SQS queue with environment awareness (`dev`, `test`, `prod`).
- `controllers/`: Helm values and configuration for platform controllers (ACK, Kro) deployed to spoke workload clusters.
