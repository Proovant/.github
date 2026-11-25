# Proovant
### Find it. Challenge it. Prove it.

Proovant is an AI-assisted smart contract security review engine designed to identify vulnerabilities, challenge candidate findings, and validate them with executable proof-of-concept tests.

We combine specialised AI analysis with adversarial validation and Foundry-based testing to make security findings more reproducible and actionable.

**[Website](https://www.proovant.com)** · **[X](https://x.com/Proovant_ai)** · **[LinkedIn](https://www.linkedin.com/company/proovant)** · **[Contact](mailto:info@proovant.com)**

## How Proovant Works

### 01 — Scope & Threat Model
Map the codebase, identify critical contracts and value flows, and establish the review scope and threat model.

### 02 — Parallel Security Analysis
Specialised agents analyse different vulnerability classes, including accounting, access control and upgrades, external calls, state flow, logic edge cases, oracle and economic design, and cross-component interactions.

### 03 — Adversarial Validation
A separate review stage challenges candidate findings, assessing reachability, impact, and whether an issue is already fixed, documented, or otherwise invalid.

### 04 — Executable Proof of Concept
Surviving candidates are developed into Foundry tests where feasible. A passing test supports the described scenario under its stated assumptions; it does not by itself guarantee exploitability in every live deployment.

### 05 — Report & Human Review
Findings are documented with severity reasoning, impact, reproduction details, assumptions, and remediation guidance. Human review is performed according to the engagement scope.

## Our Approach

- Evidence over speculation
- Adversarial validation before reporting
- Reproducible PoCs where feasible
- Clear impact, assumptions, and remediation guidance
- Transparent scope and limitations

Proovant is AI-assisted security analysis. It does not guarantee that a codebase is vulnerability-free and does not replace a comprehensive independent security audit.

## Security Reviews

See our public, approved review write-ups and remediation summaries in the [security reviews repository](https://github.com/Proovant/proovant-security-reviews).

## Get in Touch

Interested in a smart contract security review?

**[Request a review](https://www.proovant.com)**
