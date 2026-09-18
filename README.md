Markdown
# Hi there, I'm Jesse Tuohy 👋 (@trencinodin-stack)

Founder & Principal Invariant Architect at **Arcstone Adaptive Science Systems, Inc.**

Focusing on deterministic computational spines, admissibility-first systems, execution boundaries, and reproducible research into deterministic control surfaces for high-stakes computational environments.

---

## 📚 Master Research Suite & Academic Anchor

The **Arcstone Continuity Core & Admissible Computation Suite** is registered and archived across scientific repositories:

* **Primary Master Anchor (Zenodo):** [DOI: 10.5281/zenodo.22665852](https://doi.org/10.5281/zenodo.22665852)
* **Monolithic Research Archive (Figshare):** [DOI: 10.6084/m9.figshare.33477511](https://doi.org/10.6084/m9.figshare.33477511)
* **Zenodo Community Collection:** [Arcstone Continuity Core & Admissible Computation Suite](https://zenodo.org/communities/arcstone-continuity-core)
* **System Invariants:** `C_ops = 0` ∧ `Data_Egress_Sensitive = 0` ∧ `τ_override ≤ 11.99ms`
* **Suite Security Hash:** `A-77-DELTA-SHIELD-LOCKED`

The broader research suite describes architectural, formal-verification, hardware, governance, and deployment mechanisms beyond the bounded executable surfaces currently published on GitHub.

Public repositories should therefore be interpreted according to their own declared implementation boundaries rather than as complete implementations of the broader Arcstone architecture.

---

## 🔬 Core Focus Areas

- **Deterministic Systems Architecture** — Researching computational structures that place explicit deterministic constraints around otherwise probabilistic or nondeterministic computational processes.

- **Admissibility & Continuity** — Investigating bounded evaluation surfaces, temporal constraints, memory ceilings, fail-closed behavior, deterministic replay, and local continuity.

- **Execution Boundaries** — Separating deterministic evaluation, authorization, actuation, and observed effects so that computational outputs do not implicitly acquire execution authority.

- **Bare-Metal & Edge Engineering** — Exploring eBPF, low-level Rust, hardware isolation, local execution membranes, and other mechanisms described across the broader Arcstone research suite.

- **Reproducible Research** — Publishing bounded reference implementations and downstream experiments whose claims can be independently inspected, executed, and reproduced.

---

## 🛠️ Technologies & Toolkit

- **Languages:** Rust, C/C++, Python, Go, TypeScript, SQL
- **Systems & Frameworks:** `#![no_std]` Rust, eBPF, Bare-Metal Systems, Graph Theory, Distributed Systems, Capability-Oriented Architecture
- **Research Methods:** Deterministic Evaluation, Invariant Testing, Evidence Preservation, Exact Replay, Cross-Language Conformance
- **Tools:** Linux, Git, GitHub Actions, Docker, VS Code, Model Context Protocol (MCP)

---

## 📄 12-Part Technical Whitepaper Suite

| Paper | Reference Code | Canonical Title & Anchor |
| :--- | :--- | :--- |
| **Paper 0** | `WP001` | [Arcstone Computational Spine: Baseline, eBPF Kernel Protection & Enterprise RAG](https://doi.org/10.5281/zenodo.22665852) *(Master Anchor)* |
| **Paper 1** | `PHYS01` | [Theoretical Architecture and Mathematical Evolution of Classical Electrodynamics](https://doi.org/10.5281/zenodo.22677708) |
| **Paper 2** | `WP002` | [Arcstone Continuity Core: Air-Gapped Multimodal Local RAG Architecture](https://doi.org/10.5281/zenodo.22681508) |
| **Paper 3** | `WP003` | [The Sovereign NPC: Why AI Isn't Conscious—and Why That Makes It a Cognitive Exoskeleton](https://doi.org/10.5281/zenodo.22678934) |
| **Paper 4** | `WP004` | [The Autonomic Governance Operating System: Authorization-First Architecture](https://doi.org/10.5281/zenodo.22679072) |
| **Paper 5** | `WP005` | [The Negentropic Enterprise: Structural Invariants for Non-Delegable Governance](https://doi.org/10.5281/zenodo.22679481) |
| **Paper 6** | `WP006` | [Deterministic Continuity Field Nodes (CFN): Bare-Metal Substrate for Offline State Verification](https://doi.org/10.5281/zenodo.22679579) |
| **Paper 7** | `WP007` | [Deterministic State Reconstruction and Fault-Tolerant Memory Boundaries](https://doi.org/10.5281/zenodo.22679788) |
| **Paper 8** | `WP008` | [Wi-Fi 7 Multi-Link Operation (MLO) Protocol Stack: Sub-12ms Latency Clamps](https://doi.org/10.5281/zenodo.22680038) |
| **Paper 9** | `SWAP01` | [The Cascading SWaP Revolution: Eliminating Hardware Overhead via Admissible Software](https://doi.org/10.5281/zenodo.22680187) |
| **Paper 10** | `WP010` | [Architectural Analysis: The Inverted Substrate Paradigm](https://doi.org/10.5281/zenodo.22680282) |
| **Paper 11** | `PHYS02` | [Period 8 Initialization and the Femtobarn Frontier: Heavy-Ion Dynamics at Z ≥ 119](https://doi.org/10.5281/zenodo.22681286) |

---

## 📁 Public Research Repositories

Arcstone's public repositories expose bounded, reproducible reference surfaces from a broader research architecture.

They are intentionally narrower than the complete upstream research system.

### 1. Arcstone Continuity Core

[`arcstone-continuity-core`](https://github.com/trencinodin-stack/arcstone-continuity-core)

**Status:** `FROZEN / ACTIVE`  
**Role:** Upstream public Path A reference surface  
**Release:** `v1.3.1-exec`  
**Anchor:** `A-77-DELTA-SHIELD-LOCKED`

A lean deterministic reference implementation preserving selected Arcstone Continuity Core invariants and cross-language conformance behavior.

The executable Rust surface provides a portable `#![no_std]` deterministic predicate with explicit payload and temporal bounds.

The repository also preserves broader specification and research provenance associated with the Arcstone Computational Spine.

It is intentionally **not** the complete Arcstone Computational Spine and is **not** the source of canonical system authority.

Its implementation boundary should not be expanded merely because broader mechanisms appear in associated specifications, publications, or downstream research.

---

### 2. Arcstone Path A Ingress Lab

[`arcstone-path-a-ingress-lab`](https://github.com/trencinodin-stack/arcstone-path-a-ingress-lab)

**Status:** `EXPERIMENTAL / DOWNSTREAM / NON-CANONICAL / COMPLETE & FROZEN`  
**Version:** `v0.1.0`  
**Role:** External-producer ingress, evidence preservation, and deterministic replay experiment

A downstream experimental realization testing whether serialized output from an external, potentially nondeterministic producer can be preserved as exact raw bytes, evaluated through the unchanged Arcstone Continuity Core Path A predicate using explicit controlled inputs, and replayed with the same deterministic result.

The completed experimental sequence includes:

- a deterministic baseline run;
- a live external nondeterministic producer run;
- preservation of the exact produced bytes;
- explicit controlled elapsed input;
- evaluation through the unchanged Path A predicate;
- evidence capture; and
- exact replay of the preserved input and deterministic result.

The bounded result establishes evidence for external-producer ingress and deterministic replay under the tested conditions.

It does **not** establish AI safety, model alignment, model correctness, execution authorization, production security, real inference or network latency behavior, or implementation of the complete Arcstone architecture.

---

### 3. Arcstone MCP Sidecar

[`arcstone-mcp-sidecar`](https://github.com/trencinodin-stack/arcstone-mcp-sidecar)

**Status:** `ACTIVE / CANONICAL FREEZE`  
**Registry Identity:** `io.github.trencinodin-stack/arcstone-mcp-sidecar@0.1.0`  
**Crate:** `arcstone-execution-boundary` (`v0.1.0`)  
**Role:** Reference downstream execution boundary sidecar for the Arcstone Security Stack

A downstream reference sidecar published on the official Model Context Protocol (MCP) Registry, providing a deterministic execution boundary interface over standard `stdio`.

It enforces mathematical safety invariants between untrusted action producers and protected system side effects:
- **Non-Authorization Safety ($I1$):** Zero protected actuation without explicit valid authorization.
- **Single-Use Authority ($I2$):** At most one protected actuation attempt per single-use authorization token.
- **Exclusive Actuation Authority ($I3$):** Untrusted producers never directly influence protected physical resources or filesystem targets.

The completed baseline encompasses a bounded Windows authority-boundary experiment, an integrated T0–T17 adversarial validation matrix, and Execution Boundary Run 001—all hash-anchored and frozen under `v0.1.0-freeze`.

---

## 🔗 Public Research Relationship

The currently published repositories form a simple upstream/downstream research relationship:

```text
       Arcstone Continuity Core
                FROZEN
                  |
         +--------+--------+
         |                 |
         v                 v
Path A Ingress Lab    Arcstone MCP Sidecar
 COMPLETE / FROZEN     ACTIVE / CANONICAL FREEZE
```
The relationship represents a progression of research and evidence, not expansion of upstream authority.

The Continuity Core provides the frozen deterministic Path A reference surface.

The Path A Ingress Lab independently tests an external-producer boundary against that unchanged surface while preserving the producer output as raw evidence.

The Arcstone MCP Sidecar exposes a downstream execution boundary implementing Model Context Protocol (MCP) standards while preserving core safety invariants (I1,I2,I3).

A favorable Path A result remains an evaluation result only.

It does not inherently grant authorization or permission for downstream actuation.

More generally:

Plaintext
deterministic evaluation
        ≠
authorization
        ≠
actuation
        ≠
observed effect
Future downstream research may investigate additional boundaries independently without modifying the frozen Continuity Core or rewriting completed experimental evidence.

## 🧭 Research & Release Progression

* **Phase 1 — COMPLETE:** 12-part academic suite DOI registration and archival anchoring across Zenodo and Figshare.
* **Phase 2 — COMPLETE:** Publication of supporting technical and conceptual material describing the broader research architecture.
* **Phase 3 — COMPLETE / FROZEN / PUBLIC:** `arcstone-continuity-core` released as the bounded public Path A deterministic reference surface.
* **Phase 4 — COMPLETE / FROZEN / PUBLIC:** `arcstone-path-a-ingress-lab` released as a downstream experimental repository demonstrating preserved external-producer ingress and exact deterministic replay against the unchanged Path A predicate.
* **Phase 5 — COMPLETE / ACTIVE / PUBLIC:** `arcstone-mcp-sidecar` published on the official MCP Registry (`io.github.trencinodin-stack/arcstone-mcp-sidecar@0.1.0`) as an active reference execution boundary enforcing invariants $I1, I2, I3$.

Further public repositories will be added only when their experimental boundaries, evidence, documentation, and release state are independently ready for publication.

🧪 Research Discipline
Arcstone public research follows a simple working principle:

Evidence before expansion.

A repository should answer a bounded question before its scope is enlarged.

Completed evidence remains preserved.

Frozen upstream objects are not rewritten merely to incorporate later downstream discoveries.

Downstream success does not retroactively transfer authority upstream, redefine frozen semantics, or establish claims outside the tested experimental boundary.

📬 Connect & Framework Anchors
Institutional & Systems Portal: Arcstone OS — Admissibility & Governance Infrastructure

Theoretical Authority: Arcstone Science Authority — Canonical Registry of Fields, Domains & Laws

Live Edge Gateway: Arcstone L7 Edge Gateway

LinkedIn: Jesse Tuohy

X (Twitter): @founderarcstone

Substack: Arcstone OS

YouTube: @admissibilityscience

Reddit: u/AdmissibilityScience

ORCID ID: 0009-0008-4661-1540

Current Public Research Surface
Arcstone Continuity Core → Path A Ingress Lab & Arcstone MCP Sidecar

Frozen upstream reference surface → completed downstream ingress, deterministic replay evidence, and active MCP execution boundary sidecar.

Additional downstream research will be published independently when its evidence and release boundary are complete.
