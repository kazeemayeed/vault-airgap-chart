# Vault Air-Gapped Helm Chart

A production-ready Helm chart to deploy HashiCorp Vault in air-gapped Kubernetes environments such as OpenShift or internal clusters without external internet access.

## Features
- Offline-compatible (internal image registry)
- Pre/Post-install lifecycle hooks
- Configurable backup job (CronJob)
- Customizable Vault configuration

## Usage
```bash
helm install vault ./vault-airgap-chart -n vault --create-namespace
```

## Notes
- Ensure all container images are mirrored to your internal registry
- Volume storage class should be pre-created in your cluster
- You may add secrets and auto-unseal via Vault's supported mechanism (KMS/HSM/etc.)