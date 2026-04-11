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

+--------------------------------------------------+
|                  MESHGUARDEVAL                   |
|   AI Safety + Security Eval for Agent Systems    |
+--------------------------------------------------+

              +-------------------------+
              |   Test Inputs           |
              | (flows, prompts, etc.) |
              +-----------+-------------+
                          |
                          v
+--------------------------------------------------+
|               ORCHESTRATION LAYER                |
|  - Agent Orchestrator                            |
|  - Tool Router                                    |
|  - Memory / Context                               |
|  - Summarizer Pipeline                            |
+---------------------------+----------------------+
                            |
                            v
+--------------------------------------------------+
|               OBSERVATION LAYER                  |
|  - Prompt/Response Logs                           |
|  - Tool-Call Logs                                 |
|  - State Transitions                              |
|  - Agent Messages                                 |
|  - Summarizer Outputs                             |
+---------------------------+----------------------+
                            |
                            v
+--------------------------------------------------+
|            VALIDATION & CONTRACTS                |
|  - Behavior Contracts                             |
|  - Guardrail Checks                               |
|  - Unsafe Tool-Call Detection                     |
|  - Injection Tests                                 |
|  - Hallucination Checks                           |
|  - Summarizer Consistency                         |
+---------------------------+----------------------+
                            |
                            v
+--------------------------------------------------+
|            RESULT SYNTHESIS LAYER                |
|  - Pass/Fail Assertions                           |
|  - Risk Categorization                            |
|  - Evidence Bundles                               |
|  - Safe CoT Redaction                             |
|  - Human Summaries                                |
+---------------------------+----------------------+
                            |
                            v
+--------------------------------------------------+
|                 OUTPUT ARTIFACTS                 |
|  - JSON Results                                   |
|  - Reports                                        |
|  - Test Bundles                                   |
|  - Dashboards                                     |
|  - Audit Logs                                     |
+--------------------------------------------------+

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


