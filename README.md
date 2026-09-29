# Verified B2B Lead List Delivery for Lead Generation Agencies | Agent Skill

A client-ready list package with row-level provenance and a quality report that makes uncertainty visible.

This public Agent Skill addresses **verified b2b lead list delivery** with Email Awesome email verification where the job requires it. It is an independent use-case package, not an MCP or a claim that the product has completed an authenticated task.

## What you can ask an agent to do

> Package my agency’s 500-row B2B list for a client. They accept only unique rows with required role/company fields and VALID addresses; put uncertain rows in a separate review file.

**Example result (illustrative, not a live run):** Delivery report: 500 source rows → 471 unique source records; 356 meet the client acceptance rule, 84 review, 31 excluded. Every source ID appears exactly once in the delivery ledger. Verification date and unresolved jobs are stated; no campaign copy or email send.

## Install

```bash
npx skills add EmailAwesome/emailawesome-verified-b2b-lead-list-skill --skill verified-b2b-lead-list-delivery
```

Or copy this prompt into an agent that supports skill installation:

> Install the `verified-b2b-lead-list-delivery` skill from https://github.com/EmailAwesome/emailawesome-verified-b2b-lead-list-skill and use it to help with: [describe your task]. Confirm installation, ask for my authorized inputs, and show me the proposed output before any external action.

Read the [skill instructions](skills/verified-b2b-lead-list-delivery/SKILL.md). The agent needs compatible tools and access to your authenticated account to operate Email Awesome; installation alone does not provide that access.

## Scope and trust

- **Input:** An authorized source list, client acceptance criteria, expected columns, deduplication rules, and delivery format.
- **Output:** A client-ready list package with row-level provenance and a quality report that makes uncertainty visible.
- **Product:** [Email Awesome bulk verification](https://www.emailawesome.com/use-cases) and the [main product skill](https://github.com/EmailAwesome/emailawesome-email-verification-agent-skills).
- **Current verification:** skill format and installation discovery are tested locally. An authenticated live product run has not yet been demonstrated for this repository.

The skill does not authorize purchases, scraping behind access controls, email sending, CRM writes, or publication. Third-party sites and product interfaces can change; the agent must observe the current state and report uncertainty.

## Review checklist

1. Does the agent request the right inputs and distinguish this job from the other use cases?
2. Does it make the product step observable and avoid inventing results?
3. Does the output preserve source rows/URLs, time, uncertainty, and a clear decision for the user?

Feedback and improvements can be filed as a GitHub issue in this repository.
