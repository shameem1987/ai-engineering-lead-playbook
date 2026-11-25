# Agentic workflow design canvas

Fill this in **before** building any agent.

| | |
|---|---|
| **Workflow / goal** | What job is being automated? |
| **Current process and pain** | Steps, time, error rate today |
| **Inputs and data sensitivity** | What does the agent see? Anything regulated? |
| **Tools the agent may use** | Read-only vs. write; least privilege |
| **Autonomy level** | Suggest only / act with approval / act and report |
| **Human checkpoints** | Where must a person approve? |
| **Failure modes** | Wrong action, loops, prompt injection, cost blowups |
| **Guardrails** | Step limits, budgets, allow-lists, sandboxing, kill switch |
| **Evaluation** | Test set, pass criteria, regression gate in CI |
| **Observability** | Traces, logs of every tool call, cost tracking |
| **Rollback** | How to disable it and recover? |
| **Success metric** | Outcome (time saved, defects avoided), measured vs. baseline |
