# IMPLEMENTATION — Public Profile and Organization Surface

## Scope

Only public-facing organization narrative, high-level architecture concepts, engineering areas and intentionally public GitHub community-health files belong here. Detailed topology and cross-repository interfaces belong in private `.github-private`, and implementation belongs in the owning repository.

## File requirements

| Path | Responsibility |
|---|---|
| `README.md` | Public repository role, security/disclosure boundary |
| `profile/README.md` | Public organization profile and capability-level conceptual diagram |
| `IMPLEMENTATION.md` | Review-first authoring instructions and public disclosure acceptance tests |

## Implementation steps

1. Read the current public `profile/README.md`, confirm it describes the ecosystem without claiming live production status.
2. Keep only safe conceptual responsibility categories: network/access, platform/GitOps, personal/business workloads, security/operations and recoverability.
3. Never publish actual PVE topology, IPs, private DNS, identity groups, NetBird/Infisical configuration, tenant credentials, secrets, security exceptions, storage routes, recovery entrypoints or privileged administrative details.
4. Compare proposed changes with private governance *without copying* its implementation architecture. Preserve links only to public destinations that all readers can open.
5. Validate Markdown and Mermaid, scan the public diff for credentials and internal access details, and use a reviewed PR.

## Acceptance

The public organization profile is understandable without private repo access, accurately describes modular engineering capabilities, contains no internal operational topology or secret material, and makes no unsupported runtime/availability claim. Private workflows and internal controls remain in `.github-private`.
