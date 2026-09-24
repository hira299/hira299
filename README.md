<div align="center">
<img src="https://github.com/user-attachments/assets/9054c6da-dd13-4ebd-966f-e36f1356eb3b" alt="Hira Ahmed banner" width="100%" />
</div>

# Hira Ahmed

**AI Engineer | AI Automation & QA Engineer**

I build AI automation, AI agents, and LLM pipelines that keep working when models, APIs, and data misbehave. Most of my work sits where AI meets backend and cloud engineering: n8n workflows, Python services, PostgreSQL state, and AWS. QA and reliability engineering is the thread through all of it. I test the systems I build the way I test other people's: at the boundaries, at the API, and on the failure paths.

Karachi, Pakistan. Open to remote work.

[Portfolio](https://hira299.github.io/) · [LinkedIn](https://www.linkedin.com/in/hira-ahmed-4068402a7) · [Email](mailto:hira229922@gmail.com) · [ORCID](https://orcid.org/0009-0005-3219-7252)

## What I work on

- **AI automation and agents:** stateful agents, tool-using workflows, structured LLM output with validation, retries, and human escalation
- **n8n and workflow automation:** self-hosted n8n, PostgreSQL-backed workflow state, dead-letter queues, idempotent writes, Make.com
- **LLM systems:** multi-stage LLM pipelines, RAG and Corrective RAG, LangGraph, LangChain, Groq, Gemini, OpenRouter
- **Backend and cloud:** Python, FastAPI, PostgreSQL, Supabase, Docker, AWS (EC2, Lambda, EventBridge, SQS, RDS, S3), Terraform
- **QA and reliability:** B2B SaaS QA, API testing, multi-tenant isolation, RBAC, business-logic and financial-integrity testing

## Professional work (TechPotion.ai)

Production work as Backend & AI Automation Engineer. Client and internal details are not published.

- **[28K+ production AI enrichment pipeline](https://hira299.github.io/case-studies/28k-record-pipeline/):** status-driven PostgreSQL pipeline with 4 sequential LLM stages (including translation into 9 languages) over 28,000+ records; 5.6x processing speedup, as reported
- **[AWS infrastructure and cost optimization](https://hira299.github.io/case-studies/aws-cost-optimization/):** monthly AWS costs for the same platform reduced by 34%
- **[Multi-tenant B2B SaaS QA](https://hira299.github.io/case-studies/multitenant-saas-qa/):** lead QA on PharmaConnect across 20 end-to-end journeys and 6 roles; 80+ defects documented with API-level evidence and 11 critical P1 findings
- 678+ defects identified and documented across all of my QA engagements

## Research: Sentinel-Mesh and CloudFix-Bench

**Sentinel-Mesh** is a research framework for remediating Terraform cloud-security misconfigurations. An LLM proposes a candidate patch; a Z3 SMT verifier checks it against explicit security invariants defined in a Cloud Perimeter Model; a rejected patch's counterexample is fed back to the model for another attempt. The model only proposes. The verifier decides.

- **CloudFix-Bench:** 105 AWS Terraform misconfiguration cases, archived on Zenodo for reproducibility
- **Results on that benchmark:** 88/105 cases remediated (83.81%, 95% Wilson interval 75.59% to 89.64%), against 64.76% without counterexample feedback and 35.24% for a Checkov baseline
- **No security regressions observed** against the modeled invariants (0.0%, 95% interval 0.00% to 3.45%)
- **Scope:** formal guarantees hold only within the Cloud Perimeter Model. Properties outside it, such as WAF associations or logging policies, are checked by the verifier without a formal proof certificate, and an external set of 12 cases reached 6/12.

Preprint on Research Square, manuscript under review. Lead author.

[Research Square preprint](https://www.researchsquare.com/article/rs-10674271/latest) · [CloudFix-Bench on Zenodo](https://doi.org/10.5281/zenodo.20975067) · [Code](https://github.com/hira299/sentinel-mesh) · [Technical article on Medium](https://medium.com/@hira299/beyond-heuristics-formally-verifying-ai-generated-infrastructure-with-z3-smt-solvers-e95fd3a7bf95)

Also: peer reviewer for IEEE Access (5 verified reviews on [Web of Science](https://www.webofscience.com/wos/author/record/QIV-1552-2026)). B.S. Cybersecurity, Sir Syed University of Engineering & Technology.

## Selected independent builds

| Project | What it shows |
|---|---|
| [AI-Autonomous-Email-Agent](https://github.com/hira299/AI-Autonomous-Email-Agent) | Stateful n8n email agent with per-thread memory and Groq inference |
| [Cloud-Security-Audit-Compliance-Automation-Platform](https://github.com/hira299/Cloud-Security-Audit-Compliance-Automation-Platform) | AWS audit pipeline with a persistent audit trail and a DLQ replay workflow |
| [Financial-Profitability-Guardrail](https://github.com/hira299/Financial-Profitability-Guardrail) | PostgreSQL state machine that alerts only on state transitions |
| [Autonomous-Competitor-Intelligence-SEO-Pipeline](https://github.com/hira299/Autonomous-Competitor-Intelligence-SEO-Pipeline) | Scheduled AI pipeline with defensive JSON parsing and a scraper DLQ |
| [Cloud-Cost-Sentinel](https://github.com/hira299/Cloud-Cost-Sentinel) | AWS cost anomaly detection with a rolling baseline |
| [vektor-ats-diagnostics](https://github.com/hira299/vektor-ats-diagnostics) | Multimodal document parsing and weighted evaluation engine |
| [browser-forensics-reconstruction](https://github.com/hira299/browser-forensics-reconstruction) | DFIR tool that reconstructs browser session timelines |
| [aegis-realtime-voice-dispatch](https://github.com/hira299/aegis-realtime-voice-dispatch) | Real-time voice command dispatch dashboard |

## Open technical resources

- [n8n-production-resilience-patterns](https://github.com/hira299/n8n-production-resilience-patterns): retries, dead-letter queues, idempotency, replay, and explicit state for self-hosted n8n
- [enterprise-multitenant-qa-matrix](https://github.com/hira299/enterprise-multitenant-qa-matrix): test matrices and checklists for multi-tenant isolation, RBAC, APIs, and business logic

## Hire me

I take on remote projects in:

- AI automation and API integrations
- n8n workflows (cloud or self-hosted)
- AI agents and LLM pipelines
- B2B SaaS QA, API testing, and multi-tenant testing

[Portfolio](https://hira299.github.io/) · [Upwork](https://www.upwork.com/freelancers/~0178616a4e00b82166) · [Fiverr](https://www.fiverr.com/hira299) · [LinkedIn](https://www.linkedin.com/in/hira-ahmed-4068402a7) · [hira229922@gmail.com](mailto:hira229922@gmail.com)
