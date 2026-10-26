# Cuppy Pay: Three Core Security Policies

A hands-on GRC consulting project. The goal is to take a fintech with no written security policies and give it an Information Security Policy, an Access Control Policy and an Incident Response Policy, along with everything needed to make them work in practice.

Cuppy Pay is fictional. The problem it has is very real, though, and the project is built around it.

## The situation

Cuppy Pay is a 120-person fintech that processes card and bank-transfer payments for small merchants. It runs on AWS, uses Microsoft 365 and Slack, and ships a mobile app and a merchant dashboard built by an in-house team of 25 engineers. It also leans on three third parties: a card processor, a KYC provider and a managed SOC-lite service.

What it doesn't have is a single formal security policy.

Its largest banking partner wants proof of a documented security programme within four weeks, or the contract renewal is at risk. Leadership also wants to start working toward ISO/IEC 27001 certification within the year. So the policies need to pass a bank's scrutiny now and hold up as the foundation for an ISMS later.

## What this project produces

Three policies, each backed by the documents that make it enforceable:

| Policy | What it does |
|---|---|
| **Information Security Policy** | Sets direction and ownership. Every other policy hangs from this one. |
| **Access Control Policy** | The most common preventive control, and usually the first thing auditors and bank partners test. |
| **Incident Response Policy** | Shows the company can handle things going wrong, not only prevent them. |

I picked these three because they cover governance, prevention and response, and because they map cleanly to ISO 27001 (Clause 5.2 and Annex A), SOC 2 criteria and the questions a typical due-diligence questionnaire asks.

For each policy you'll find:

- The policy itself, written to one consistent standard
- Mapping to at least two frameworks
- Supporting standards, procedures and templates
- A risk-based reason behind every major requirement
- Evidence of stakeholder consultation, review and formal approval

Across all three, the project also delivers a rollout and awareness plan and a measurement plan that shows how compliance will be monitored.

## What "done" looks like

A bank auditor should be able to read the policies, then ask Cuppy Pay staff about them, and find that what's written matches what people actually do, or what they are credibly planning to do. A folder of polished documents that nobody follows doesn't count.

## Scope

**In scope:** all employees, contractors, systems, cloud environments and information assets, including data processed on behalf of merchants.

**Out of scope:** merchant-side security, physical security (a later piece of work), and technical implementation of tooling beyond what's needed to define requirements.

## Assumptions

These are the starting conditions I worked from. If you're running this with a real client or a class, change them to fit.

- The CEO is the executive sponsor and the CTO acts as interim security lead.
- There is no dedicated CISO, SOC or full-time compliance staff.
- Identity runs through Microsoft Entra ID with SSO into most tools, but a few legacy systems still use local accounts.
- There have been two minor phishing incidents in the past year, both handled informally over Slack.

## Who's involved

| Role | Part they play |
|---|---|
| CEO (sponsor) | Approves the Information Security Policy and owns risk appetite |
| CTO | Owns technical controls, interim security lead |
| Head of HR | Joiner, mover and leaver process, alignment with disciplinary procedures |
| Head of Engineering | Privileged access and production environments |
| Legal / Compliance Officer | Regulatory notification duties and contracts |
| IT Administrator | Day-to-day access administration |
| Customer Support Lead | Customer communication during incidents |
| Bank partner liaison | The outside audience for the evidence pack |

## Timeline

Four weeks, one phase each.

| Week | Phase | Main output |
|---|---|---|
| 1 | Discovery and risk context | Stakeholder notes, asset and data overview, top-10 risk list, gap summary |
| 2 | Drafting | First drafts of all three policies and a policy architecture map |
| 3 | Supporting documents and review | Standards, procedures, RACI, templates, reviewer comments resolved |
| 4 | Approval, rollout and handover | Signed policies, awareness plan, metrics sheet, evidence pack |

## How to use this

If you're here to learn, work through the weeks in order. Each phase builds on the last, and the risk list from week 1 is what justifies the requirements you write in week 2.

If you're running it as a class or workshop, the assumptions above are the easiest thing to change. Swap in a different company size, cloud provider or set of third parties and the policies will need to change with them.

If you're borrowing a template, check it against your own organisation first. A policy copied wholesale usually ends up describing a company that doesn't exist.

## Notes

Cuppy Pay and everyone in it are made up. Any resemblance to a real company is a coincidence.
