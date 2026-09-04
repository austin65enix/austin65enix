# Austin Hsieh

**Cloud · Observability · Security · AI Runtime Governance**

I build systems that make **automated and AI-driven actions observable, attributable, and governable** — from infrastructure telemetry and event evidence to authorization and runtime execution.

My current focus is **process-to-execution governance continuity**: keeping observation, qualification, decision, authorization, execution, and outcome distinct while preserving enough evidence to reconstruct what actually happened.

I work primarily through **specification-driven, agent-assisted engineering**: define the boundary, acceptance criteria, and failure conditions first; use coding agents to implement within that scope; then qualify the result against evidence.

---

## Selected Work

### [Governance Event Core](https://github.com/austin65enix/governance-event-core)

An implementation-neutral model for representing and semantically qualifying governance events.

Core principles include:

* preserve source event identity;
* do not infer causality from timestamps alone;
* do not collapse authority stages;
* preserve negative authority information;
* prefer absent lineage to invented lineage;
* **qualification does not grant authority**.

**Focus:** AI governance · event semantics · authority lineage · conformance

---

### [ENYRAX Cloud Portal](https://github.com/austin65enix/enyrax-cloud-portal)

A cloud-hosted enterprise operations platform prototype integrating:

* SOC monitoring
* ServiceOps
* ProjectOps
* FastAPI services
* Nginx / HTTPS
* AI-assisted operational workflows

**Live deployment:** https://portal.soc-monitoring.dev

**Focus:** Cloud architecture · operations platform · API integration · deployment

---

### [Observatory OPS](https://github.com/austin65enix/observatory-ops)

An operational intelligence and observability architecture connecting:

```text
Telemetry
   ↓
Events
   ↓
Evidence
   ↓
Operational Intelligence
   ↓
Governance
```

The project explores how monitoring and observability can evolve into evidence-backed operational and governance workflows.

**Focus:** Observability · event correlation · evidence preservation · operational governance

---

## Foundation

### [SOC Monitoring & SIEM Lab](https://github.com/austin65enix/soc-monitoring-siem-lab)

A security operations architecture lab focused on the **incident lifecycle rather than tool installation alone**.

```text
Detection
→ Notification
→ Correlation
→ Investigation
→ Root Cause
→ Recovery
→ Optimization
```

Built around Wazuh, Zeek, Graylog, Zabbix, and Linux-based monitoring environments.

---

## Engineering Principles

```text
Observation ≠ Qualification
Qualification ≠ Decision
Decision ≠ Authorization
Authorization ≠ Execution
Execution ≠ Outcome
```

I prefer systems that:

* preserve provenance and execution evidence;
* fail closed instead of producing plausible guesses;
* distinguish implemented controls from documented intentions;
* make authority boundaries explicit;
* retain enough evidence for independent review;
* keep human authorization where consequential actions require it.

---

## Current Direction

```text
Infrastructure Operations
        ↓
Security Monitoring
        ↓
Observability
        ↓
Event & Evidence Engineering
        ↓
AI / Agent Runtime Governance
        ↓
Process-to-Execution Governance Continuity
```

I am especially interested in the intersection of:

**Cloud Infrastructure · Platform Engineering · Observability · Product Security · AI Agent Governance**

---

## Tech & Tools

**Infrastructure**
Linux · AWS / Cloud · Nginx · Docker · Kubernetes · Terraform

**Backend & Automation**
Python · FastAPI · REST APIs · PostgreSQL

**Observability & Security**
Wazuh · Zeek · Graylog · Zabbix · OpenTelemetry concepts

**Engineering Workflow**
Git · GitHub Actions · Codex / AI coding agents · specification-driven development

---

> **The goal is not merely to automate execution.
> The goal is to know what was observed, what was decided, who or what was authorized, what actually executed, and what evidence remains afterward.**
