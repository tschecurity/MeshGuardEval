# MeshGuardEval  
### Hybrid AI Safety + Security Evaluation Harness for Multi‑Agent Systems

AI systems are evolving faster than our ability to evaluate them — and that gap is where real risk hides.  
**MeshGuardEval** is a hybrid AI safety and security evaluation harness designed to test multi‑agent systems the way real adversaries and real users actually interact with them.

Instead of treating QA, security, and LLM behavior as separate problems, MeshGuardEval unifies them into a **single, contract‑driven evaluation pipeline**.

---

## Features

- **UI Workflow Validation**  
  AC‑style functional checks for agent workflows and tool‑calling paths.

- **Adversarial Prompt Testing**  
  Injection attempts, unsafe tool‑call triggers, policy bypass attempts.

- **LLM Behavior Contracts**  
  Hallucination detection, guardrail enforcement, summarizer correctness.

- **Summarizer Consistency Checks**  
  Drift detection, multi‑agent agreement validation.

- **Reproducible CI‑Friendly Artifacts**  
  JSON logs, evidence bundles, and reviewer‑ready reports.

---

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                              MESHGUARDEVAL                                   │
│     Hybrid AI Safety + Security Evaluation Harness for Multi‑Agent Systems   │
└──────────────────────────────────────────────────────────────────────────────┘

                      ┌──────────────────────────┐
                      │   Test Scenario Inputs    │
                      │  (UI flows, prompts,     │
                      │   adversarial cases,     │
                      │   policy contracts)      │
                      └─────────────┬────────────┘
                                    │
                                    ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                           ORCHESTRATION LAYER                                │
│  Multi‑Agent Mesh → Routes scenarios through agents, tools, and summarizers  │
│                                                                              │
│  • Agent Orchestrator                                                        │
│  • Tool‑Call Router                                                          │
│  • Memory / Context Manager                                                  │
│  • Summarizer Pipeline                                                       │
└───────────────┬──────────────────────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                           OBSERVATION LAYER                                  │
│  Captures everything the system does during evaluation                       │
│                                                                              │
│  • Prompt/Response Capture                                                   │
│  • Tool‑Call Logs                                                            │
│  • State Transitions                                                         │
│  • Agent‑to‑Agent Messages                                                   │
│  • Summarizer Outputs                                                        │
└───────────────┬──────────────────────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                         VALIDATION & CONTRACTS                               │
│  Applies safety, security, and correctness rules to observed behavior        │
│                                                                              │
│  • Behavior Contracts (MAITE‑style)                                          │
│  • Guardrail Enforcement Checks                                              │
│  • Unsafe Tool‑Call Detection                                                │
│  • Injection Pattern Tests                                                   │
│  • Hallucination / Fabrication Checks                                        │
│  • Summarizer Consistency Validation                                         │
│  • Policy / Limit Enforcement                                                │
└───────────────┬──────────────────────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                         RESULT SYNTHESIS LAYER                               │
│  Converts raw findings into reviewer‑ready artifacts                         │
│                                                                              │
│  • Pass/Fail Assertions                                                      │
│  • Risk Categorization                                                       │
│  • Evidence Bundles (inputs + outputs)                                       │
│  • Chain‑of‑Thought Redaction (safe)                                         │
│  • Human‑Readable Summaries                                                  │
└───────────────┬──────────────────────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                           OUTPUT ARTIFACTS                                   │
│                                                                              │
│  • CI‑Friendly JSON Results                                                  │
│  • Reviewer‑Ready Reports                                                    │
│  • Reproducible Test Bundles                                                 │
│  • Scenario‑Level Dashboards                                                 │
│  • Logs for Red‑Team / GovTech Audits                                        │
└──────────────────────────────────────────────────────────────────────────────┘

```
# Why MeshGuardEval Exists

Modern AI systems are not just models — they are:

- multi‑agent orchestrators  
- tool‑calling frameworks  
- summarizers  
- memory layers  
- UI surfaces  
- identity and permission systems  

Traditional QA doesn’t cover this.  
Traditional security testing doesn’t cover this.  
Traditional LLM evaluation doesn’t cover this.

MeshGuardEval bridges that gap by treating AI systems as **full‑stack, adversarially exposed, safety‑critical software**, not isolated models.

---

## Who This Is For

MeshGuardEval is designed for teams working on:

- AI Safety  
- GovTech Evaluation  
- Red‑Team Automation  
- Multi‑Agent Reliability  
- LLM Guardrail Validation  
- AI Quality Engineering  

If you’re exploring these areas, this framework sits directly at that intersection.

---

## Why It Matters

AI systems are becoming infrastructure.  
Infrastructure requires evaluation that is:

- systematic  
- adversarial  
- safe  
- contract‑driven  
- reproducible  

MeshGuardEval is a step toward that future.

It provides a structured way to evaluate complex systems across multiple layers — from configuration and client behavior to schema integrity and semantic consistency — and scales as platforms evolve.


