### Hello there! I'm Shristi 👋

```text
┌────────────────────────────────────────────────────────────────────────┐
│ profile   CS Undergrad | ML Infrastructure , Cloud-Native Orchestration,
| Distributed systems, Backend/Fullstack, Systems Engineering, MlOps    │
│ trust     Active Contributor @kubeflow under maintainer guidance      │
│ impact    Built core SDK compiler fixes & automated LLM triage tools  │
│ strength  Distributed workflow engines, Pipeline IR spec serialization │
└────────────────────────────────────────────────────────────────────────┘
```
### Core Stack:
Python • Go • Kubernetes • Docker • Argo Workflows • LangGraph • Git

### Current Tackling Issue:
https://github.com/kubeflow/pipelines/issues/13239  area/sdk
### And all opened PRs:

- https://github.com/kubeflow/pipelines/pull/13707  ---> this PR fixes the issue #13239 - runtime bug where dsl.ParallelFor with a custom name brreaks downstream dsl.Collected output resolution at runtime.
to ensure output resolution works, taskInfo.name is now aligned to the internal system ID (e.g., for-loop-2), addressed the sibling issue for same loops names.

- https://github.com/kubeflow/mcp-server/pull/84 ---> This KEP proposes the implementation of an agentic kfp-generator skill within the kubeflow-mcp-server. This tool allows AI agents to translate natural language user prompts into functional Kubeflow Pipeline (KFP) v2 Python code.


### 📈 Open Source Footprint
- 📌 [Selected Engineering Highlights](./highlights.md) — A deep dive into my core contributions.

- 📦 [Kubeflow Pipelines Portfolio](https://github.com/kubeflow/pipelines/pulls?q=is%3Apr+author%3Amodichika) — Tracking my compiler & agentic workflow PRs.
