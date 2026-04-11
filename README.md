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

## Architecture

┌──────────────────────────────────────────────────────────────┐
│                        MESHGUARDEVAL                          │
│     Hybrid AI Safety + Security Evaluation for Agent Systems  │
└──────────────────────────────────────────────────────────────┘

                   ┌────────────────────────────┐
                   │     Test Scenario Inputs    │
                   │ (UI flows, prompts, policy) │
                   └──────────────┬──────────────┘
                                  │
                                  ▼
┌──────────────────────────────────────────────────────────────┐
│                     ORCHESTRATION LAYER                      │
│  Routes scenarios through agents, tools, memory, summarizers │
│                                                              │
│  • Agent Orchestrator                                        │
│  • Tool‑Call Router                                          │
│  • Context / Memory Manager                                  │
│  • Summarizer Pipeline                                       │
└───────────────┬──────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────┐
│                     OBSERVATION LAYER                        │
│  Captures all system behavior during evaluation              │
│                                                              │
│  • Prompt/Response Capture                                   │
│  • Tool‑Call Logs                                            │
│  • State Transitions                                         │
│  • Agent‑to‑Agent Messages                                   │
│  • Summarizer Outputs                                        │
└───────────────┬──────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────┐
│                 VALIDATION & CONTRACTS                        │
│  Applies safety, security, and correctness rules              │
│                                                              │
│  • Behavior Contracts (MAITE‑style)                           │
│  • Guardrail Enforcement                                      │
│  • Unsafe Tool‑Call Detection                                 │
│  • Injection Pattern Tests                                    │
│  • Hallucination Checks                                       │
│  • Summarizer Consistency                                     │
│  • Policy / Limit Enforcement                                 │
└───────────────┬──────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────┐
│                 RESULT SYNTHESIS LAYER                        │
│  Converts raw findings into reviewer‑ready artifacts          │
│                                                              │
│  • Pass/Fail Assertions                                       │
│  • Risk Categorization                                        │
│  • Evidence Bundles                                           │
│  • Safe CoT Redaction                                         │
│  • Human‑Readable Summaries                                   │
└───────────────┬──────────────────────────────────────────────┘
                │
                ▼
┌──────────────────────────────────────────────────────────────┐
│                     OUTPUT ARTIFACTS                          │
│                                                              │
│  • CI‑Friendly JSON Results                                   │
│  • Reviewer‑Ready Reports                                     │
│  • Reproducible Test Bundles                                  │
│  • Scenario Dashboards                                        │
│  • Logs for Red‑Team / GovTech Audits                         │
└──────────────────────────────────────────────────────────────┘

---

## Why MeshGuardEval Exists

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


