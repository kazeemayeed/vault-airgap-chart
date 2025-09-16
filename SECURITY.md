# Security Policy

## Supported Versions

We release patches and updates for **vault-airgap-chart** on the `main` branch.  
The latest release is always the **only actively supported version**.  

| Version     | Supported |
|-------------|------------|
| main branch | ✅ Yes     |
| older tags  | ❌ No      |

If you are using an older version, please upgrade to the latest release.

---

## Reporting a Vulnerability

If you discover a security issue, please **do not open a public GitHub issue**.  
Instead, report it responsibly:

1. git checkout -b feature/<short-description>
# or
git checkout -b fix/<short-description> 

2. **Do not** share exploit details publicly until the issue is resolved.  

3. We will acknowledge your report within **48 hours** and provide a timeline for remediation.

---

## Disclosure Policy

- We follow a **responsible disclosure** model:
  - Issues are privately investigated and patched before being publicly disclosed.
  - A security advisory will be published in this repository once a fix is available.
- Please give us reasonable time to resolve the issue before sharing publicly.

---

## Security Best Practices for Users

When deploying this chart in production, we recommend:
- Always using the **latest release**.
- Keeping Helm and Kubernetes versions up-to-date.
- Scanning container images for vulnerabilities.
- Running Vault in **least privilege** mode (restrict RBAC).
- Enabling **TLS/SSL** and following Vault’s official [security guidance](https://developer.hashicorp.com/vault/docs/security).

---

## Acknowledgements

We deeply appreciate responsible disclosures that help keep **vault-airgap-chart** safe and reliable for the community.
