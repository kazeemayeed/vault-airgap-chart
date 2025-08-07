# Vault Air-Gapped Helm Chart

This Helm chart deploys HashiCorp Vault in an air-gapped, production-ready configuration, suitable for secure and offline Kubernetes clusters.

## Features

- Air-gapped image support
- Backup configuration options
- Pre/post-install lifecycle hooks
- RBAC and service account customization
- Persistent storage support

## Usage

```bash
helm install vault-airgap ./vault-airgap --values my-values.yaml