# TIBET / ZTIP Conformance — atlas

> **Canonical repos: https://github.com/Jtel-ZTIP-w3c**
> This is a founder mirror for discoverability. **Open issues and PRs on the canonical repos**, not here.

A one-screen map of the runnable interop conformance families. Each is independent, Apache-2.0,
and follows the same rule: **the vectors are the contract, bring your own verifier.**

```
ztip-conformance        identity / attestation / freshness / jis:-namespace   (v1: VINK attestation)
tibet-comms-conformance resolve · route · deliver · reject · prove a message
tibet-evidence-conformance store · seal · trace · restore · report   (owns TimeVector + UPIP)
tibet-security-conformance allow / deny / quarantine / null-route — fail closed
```

- Ecosystem index: https://github.com/Humotica/conformance
- Hub / docs: https://jtel-ztip-w3c.github.io
- Demo app (ID-Drop): https://github.com/Jtel-ZTIP-w3c/ID-Drop

Why open: an interop standard is only credible if anyone can re-run the claims without trusting
the vendor. Open the standard and the vectors; the value is in the implementation and operation.
