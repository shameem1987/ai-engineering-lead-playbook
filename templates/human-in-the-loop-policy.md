# Human-in-the-loop policy (template)

| Autonomy level | Examples | Requirement |
|---|---|---|
| **L0 Suggest** | Code completion, draft text | Engineer reviews before use |
| **L1 Act with approval** | Open PR, post a comment, run a migration in staging | Explicit human approval per action |
| **L2 Act and report** | Auto-label issues, re-run flaky tests | Logged, reversible, sampled audits |
| **L3 Autonomous** | (rare) | Only for low-risk, reversible tasks with strong evals and a kill switch |

Never autonomous: production data changes, deployments to production, access-control changes, spending above a set limit.
