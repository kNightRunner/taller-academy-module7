# Taller Academy — Module 7: Translate, Ask, Learn

**Practice lab:** Translate, Ask, Learn  
**Project area:** Backend engineering — GraphQL integrations  
**Selected work:** External service error investigation during the last quarter  
**Evidence:** Self-reported experience and conversations; no private client material is included.

## Exercise 1 — The Translation Ladder

**Level 1 — Implementation.** I investigated failed calls to an external backend dependency used by a GraphQL integration, identified the affected interactions, and recorded the findings through the team's tracking and communication channels.

**Level 2 — Technical effect.** The investigation made the dependency failure and its integration impact easier for the responsible engineers to diagnose and follow up; it did not, by itself, resolve the underlying external-service defect.

**Level 3 — User effect.** A person using a feature that depends on this integration may have to wait longer or encounter an error when the supporting service fails; my investigation helped the teams understand the source of that disruption so they could address it.

**Level 4 — Business effect.** Dependable integration behavior matters for customer transaction flows and operational reliability. Making this failure actionable helped the team manage a potential risk to those flows; a reduction in failed transactions, support contacts, or response times has **not** been measured or claimed.

### Stranger test

**Status: Completed (self-reported).** I explained the issue without internal service names to someone outside the project, and they understood the main point: a supporting service problem could interfere with how quickly and reliably a user completes an action.

**Lesson:** Starting with the user experience is more accessible than listing internal components. The specific person's verbatim response was not recorded, so this is a summarized account rather than a quote.

## Exercise 2 — Business Fact Sheet

| Business question | Current understanding | Confidence / source |
| --- | --- | --- |
| How does the client generate revenue? | Through transactions. | Learner-reported; financial model details not disclosed. |
| Who uses or depends on the work? | End customers, internal product teams, and other engineers/services using GraphQL integrations. | Learner-reported. |
| What is the team's main roadmap focus this quarter? | Delivery of new features. | Learner-reported. |
| Which technical metrics does the team monitor? | GraphQL query response times and error counts. | Learner-reported. |
| Which two or three *product* KPIs is this area judged on? | **Awaiting product stakeholder response.** | Question sent; answer not yet received. |
| What does a good quarter look like for the client manager? | **Awaiting client manager response.** | Question sent; answer not yet received. |

### Two bounded stakeholder questions — sent

**To product stakeholder:** “What are the two or three numbers this product area is judged on?”

**Status:** Sent. No reply recorded yet.

**To client manager:** “What does a good quarter look like for you, so I can make sure what I am doing helps?”

**Status:** Sent. No reply recorded yet.

I will not invent KPIs, quarterly targets, or management priorities while the answers are pending. Technical metrics are not automatically evidence of increased revenue or customer satisfaction.

### Payoff question: Is my current sprint work the most valuable thing I could be doing?

**Current assessment: Yes, provisionally.** Building GraphQL integration capabilities supports the team's stated new-feature roadmap, while investigating dependency failures helps manage reliability risks to those features. I will revisit that assessment once the product stakeholder and client manager clarify their measures of success.

## Exercise 3 — Ask One Real Question

**Context:** During backend integration work, a requested implementation may not fully communicate the outcome stakeholders expect.

**Intent and question asked:** “I want to make sure I am solving the right problem here. What is the outcome we are going for?”

**Status:** Asked; response pending.

**Answer received:** None recorded yet.

**Did anything change?** No scope or priority change is attributed to the question at this point. When a reply arrives, I will compare the desired outcome against the proposed solution and clarify acceptance criteria if necessary.

**Reflection:** Asking about outcomes—not only implementation details—can uncover hidden assumptions before code is written. The actual consequence of this particular conversation remains open.

## Follow-up log

| Question / check | State | Next action |
| --- | --- | --- |
| Stranger test | Complete, per learner | Keep future explanations at the user-effect level first. |
| Product area KPIs | Sent; pending reply | Record exact metrics and whether the current work moves them. |
| Client manager's definition of a good quarter | Sent; pending reply | Compare priorities with sprint commitments. |
| Outcome question for a real task | Asked; pending reply | Record the response and any decision it changes. |

## Self-check

- [x] Translated one real piece of work across four levels.
- [x] Included a person doing something at Level 3.
- [x] Connected Level 4 to transaction reliability without inventing quantified results.
- [x] Completed the stranger test (self-reported).
- [x] Identified revenue model, consumers, roadmap priority, and technical metrics.
- [x] Sent the two bounded stakeholder questions.
- [x] Answered the payoff question provisionally.
- [x] Asked a real question about the intended outcome.
- [ ] Recorded stakeholder responses and any resulting decision changes.

## Privacy and evidence boundaries

This is a public, sanitized educational submission. It contains no client names, internal service names, Jira IDs, confidential business details, or proprietary source code. Self-reported facts, pending conversations, anticipated user effects, and measured outcomes are kept distinct.
