# Hi, I'm Jenny Yang 😊

I build and evaluate AI agents, with a focus on security and user experience.

Previously a PM intern at [Cloudflare](https://blog.cloudflare.com/certificate-transparency-monitoring-ga/), helping ship Certificate Transparency Monitoring to GA across 650K+ domains. M.S. Information Science at UT Austin · May 2027.

[Portfolio](https://jjjjeny.github.io/) · [LinkedIn](https://www.linkedin.com/in/jenny-y/) · [Email](mailto:yungching68@gmail.com)

## Selected work

### [Contract Review Agent](https://github.com/JJJJeny/contract-review-agent)

*Agentic AI · Team coursework*

Co-built an agent that checks vendor contracts against a risk rubric, cites clauses, and suggests revisions. Evaluated on 11 held-out contracts: **70% verdict accuracy vs. 50% for the RAG baseline**, with false alarms, missed risks, and cost tracked separately.

[Demo setup](https://github.com/JJJJeny/contract-review-agent#run-the-demo) · [Architecture](https://github.com/JJJJeny/JJJJeny/blob/main/projects/contract-review-agent.md) · [Evaluation](https://github.com/JJJJeny/contract-review-agent#results-at-a-glance) · [Code](https://github.com/JJJJeny/contract-review-agent)

### [Agentic Skill Unlearning](https://jjjjeny.github.io/projects/agentic-unlearning/)

*AI evaluation · Research at UT Austin · Preliminary results*

Testing whether a coding agent forgets a skill after its stored context is removed. Captured model requests and compared task behavior: **clearing the measured inputs did not establish behavioral forgetting**. This is runtime-context removal, not model-weight unlearning.

[Study walkthrough](https://jjjjeny.github.io/projects/agentic-unlearning/) · [Architecture](https://jjjjeny.github.io/projects/agentic-unlearning/#method) · [Findings & limitations](https://jjjjeny.github.io/projects/agentic-unlearning/#input-result)

### [Security Findings → Splunk](https://github.com/JJJJeny/security-findings-to-splunk)

*Security integration · PM assessment prototype*

Built a pipeline to validate forensic findings, map fields to Splunk's Common Information Model, and send events through HTTP Event Collector. In a Splunk Cloud trial, **199 of 200 sample findings were ingested; one was quarantined**.

[Demo setup](https://github.com/JJJJeny/security-findings-to-splunk#how-to-run) · [Architecture](https://github.com/JJJJeny/security-findings-to-splunk#architecture) · [Run evidence](https://github.com/JJJJeny/security-findings-to-splunk/tree/main/evidence/splunk-exports) · [Code](https://github.com/JJJJeny/security-findings-to-splunk)

---

Looking for full-time product roles after May 2027 in AI platforms, developer tools, and security.
