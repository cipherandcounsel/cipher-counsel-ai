# Agentic AI Content Workflow

Governance documentation for a five agent workflow that supports digital safety education content for [cipherandcounsel.com](https://www.cipherandcounsel.com).

Author: Cipher and Counsel

## Status

This repository documents the design stage of the workflow. Controls are mapped to the NIST AI Risk Management Framework and marked Designed or Verify in the governance document. Nothing here claims a completed build or test result.

## Governance document

[AI Governance Agentic Workflow (PDF)](AI%20Governance%20Agentic%20Workflow.pdf)

The document maps the workflow to the four NIST AI RMF 1.0 functions (Govern, Map, Measure, Manage). It also includes a risk register and a list of open items to close before the workflow is described as complete.

## The five agents

Each agent has one defined job.

| Agent | Role |
|---|---|
| Research | Sources new digital safety tips and threat intelligence from credible sources |
| Content Generation | Drafts posts, captions, and newsletter copy from research output |
| Scheduling | Queues and publishes approved content |
| Email | Manages subscriber capture and the nurture sequence |
| Delegation | Assigns tasks across the other agents and tracks status |

## Governance controls in the design

- **Human approval:** A person approves what publishes. Approval checkpoints decide what releases automatically and what needs review.
- **Traceability:** Agent output is logged to dated files.
- **Source standards:** Research follows primary source criteria.
- **Youth content:** Framing is age appropriate, reviewed by a person, and requires guardian consent before minors are involved directly.
- **Testing plan:** Each agent is tested alone, then the full chain end to end. A peer stress tests the workflow without guidance, and failure modes are documented.

## Tools

Claude Code and Codex.

## Open items

1. Confirm the design notes file lists data flows and tool access for each agent.
2. Record which actions publish automatically and which require approval.
3. Complete the peer stress test and file the failure mode log.
4. Add sample logged outputs from each agent to this repository.

## References

- [NIST AI Risk Management Framework 1.0 (NIST AI 100-1)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
- [NIST Generative AI Profile (NIST AI 600-1)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)
