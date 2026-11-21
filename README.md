# Agentic AI Security & SOC Automation Lab

**One-Line Goal:** Securing LLM, RAG, and autonomous agent architectures against prompt injection and tool abuse while engineering safe, human-in-the-loop AI agents for SOC alert triage and enrichment.

---

## Why This Repository Exists

With **5 years of software engineering experience building full-stack and AI/RAG platforms** combined with hands-on **banking SOC engineering**, this repository bridges two critical disciplines:
1. **Securing AI Systems (AI Security Engineering):** Defending LLM applications, RAG pipelines, and tool-calling agents against OWASP LLM Top 10 & MITRE ATLAS threats.
2. **AI for Security Operations (SOC Automation):** Designing auditable, sandboxed, least-privilege AI agents that assist SOC analysts with alert triage, threat intel enrichment, and incident reporting.

---

## Skills Demonstrated

- **LLM & Agent Threat Modeling:** Mapping trust boundaries, tool-calling attack trees, and indirect prompt injection paths across multi-agent and RAG architectures (OWASP LLM Top 10 / MITRE ATLAS).
- **Prompt Injection & Tool-Abuse Defense:** Reproducible labs testing direct/indirect prompt injection, data exfiltration via tool calls, and layered detection/defense patterns.
- **RAG Security Engineering:** Document-level access control (ACL-aware retrieval), knowledge-base poisoning detection, PII scrubbing, and retrieval validation.
- **Secure Agent Architecture:** Least-privilege tool schemas, mandatory Human-in-the-Loop (HITL) approval gates for destructive/containment actions, container sandboxing, and immutable audit trails.
- **SOC Automation Agents:** Building and evaluating practical AI agents for L1 alert triage, IOC enrichment, and structured incident report drafting.
- **Safety Evals & Guardrails:** Automated red-team evaluation suites, deterministic input/output guardrails, and policy-as-code enforcement.

---

## Repository Structure

```text
agentic-ai-security/
├── 00-foundations/
│   ├── agentic-risks/
│   ├── glossary/
│   ├── llm-threat-landscape/
│   └── owasp-llm-top-10/
├── 01-threat-modeling/
│   ├── agent-architectures/
│   ├── attack-trees/
│   ├── mitigations/
│   └── trust-boundaries/
├── 02-prompt-injection-lab/
│   ├── defenses/
│   ├── detection/
│   ├── direct/
│   ├── indirect/
│   └── tool-abuse/
├── 03-rag-security/
│   ├── access-control/
│   ├── data-poisoning/
│   ├── evaluation/
│   └── retrieval-filtering/
├── 04-secure-agent-design/
│   ├── audit-logging/
│   ├── human-in-the-loop/
│   ├── least-privilege-tools/
│   └── sandboxing/
├── 05-soc-automation-agents/
│   ├── alert-triage-agent/
│   ├── enrichment-agent/
│   ├── evaluation-and-safety/
│   └── reporting-agent/
├── 06-evals/
│   ├── metrics/
│   ├── red-team-prompts-for-own-systems/
│   └── test-cases/
├── 07-guardrails/
│   ├── input-validation/
│   ├── output-filtering/
│   └── policy-as-code/
├── assets/images/
├── docs/
└── templates/
```

---

## How to Use This Repository

1. **SOC & SOAR Hiring Managers:** Start at [`05-soc-automation-agents/`](./05-soc-automation-agents/) and [`04-secure-agent-design/`](./04-secure-agent-design/) to see how AI agents can safely accelerate SOC triage and enrichment with full auditability.
2. **Application & AI Security Engineers:** Explore [`01-threat-modeling/`](./01-threat-modeling/), [`02-prompt-injection-lab/`](./02-prompt-injection-lab/), [`03-rag-security/`](./03-rag-security/), and [`07-guardrails/`](./07-guardrails/).
3. **Safety & Confidentiality:** All prompt-injection and red-team evaluation prompts in `06-evals/` are strictly designed to test the local lab agents in this repository. All sample alerts and RAG corpora use synthetic or public datasets.

---

## Module Status Table

| Module | Sub-Modules | Status | Key Deliverable |
| :--- | :--- | :--- | :--- |
| [`00-foundations`](./00-foundations/) | `llm-threat-landscape`, `owasp-llm-top-10`, `agentic-risks`, `glossary` | `TODO` | OWASP LLM Top 10 & MITRE ATLAS mapping for agentic systems |
| [`01-threat-modeling`](./01-threat-modeling/) | `agent-architectures`, `trust-boundaries`, `attack-trees`, `mitigations` | `TODO` | Threat models & trust-boundary diagrams for RAG and tool-calling agents |
| [`02-prompt-injection-lab`](./02-prompt-injection-lab/) | `direct`, `indirect`, `tool-abuse`, `detection`, `defenses` | `TODO` | Reproducible prompt injection & tool-abuse sandbox labs and defenses |
| [`03-rag-security`](./03-rag-security/) | `data-poisoning`, `access-control`, `retrieval-filtering`, `evaluation` | `TODO` | ACL-enforced RAG pipeline with poisoning & leakage mitigations |
| [`04-secure-agent-design`](./04-secure-agent-design/) | `least-privilege-tools`, `human-in-the-loop`, `sandboxing`, `audit-logging` | `TODO` | Reference architecture for least-privilege, HITL-gated AI agents |
| [`05-soc-automation-agents`](./05-soc-automation-agents/) | `alert-triage-agent`, `enrichment-agent`, `reporting-agent`, `evaluation-and-safety` | `TODO` | Safe SOC triage, enrichment & reporting agents running on lab alerts |
| [`06-evals`](./06-evals/) | `test-cases`, `red-team-prompts-for-own-systems`, `metrics` | `TODO` | Automated adversarial evaluation suite & safety metrics |
| [`07-guardrails`](./07-guardrails/) | `input-validation`, `output-filtering`, `policy-as-code` | `TODO` | Deterministic & classifier-based guardrails as code |
