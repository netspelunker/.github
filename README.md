# Netspelunker — Public Organization Metadata

This repository owns the **public organization profile** in [profile/README.md](profile/README.md). It describes the engineering problems, capabilities and outcomes behind the Netspelunker ecosystem without disclosing implementation topology, private routes, identities, hostnames, IP addresses, ports, credentials, recovery procedures or internal repository contents.

The private organization-wide engineering rules, contracts and reusable workflows are stored in the separate private `.github-private` repository. Member repositories own their own implementation details. No internal GitHub configuration is automatically inherited from `.github-private`: any reusable workflow must be consumed explicitly where GitHub permissions allow.

This repository is not the deployment source for infrastructure, Kubernetes tenants, NetBird, or any public application. See [IMPLEMENTATION.md](IMPLEMENTATION.md) for its publication, change and validation contract.

**Status:** Public-facing product and engineering profile. This documentation does not assert that proposed infrastructure is deployed or operational.
