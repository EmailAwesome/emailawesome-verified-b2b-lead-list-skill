# Verified B2B Lead List Delivery for Lead Generation Agencies

**Official Email Awesome agent skills** · Published and maintained by [EmailAwesome](https://github.com/EmailAwesome), the official Email Awesome GitHub organization. [Visit Email Awesome](https://www.emailawesome.com/).

A client-ready list package with row-level provenance and a quality report that makes uncertainty visible. This Agent Skill helps **b2b lead-generation and data agencies delivering a list to a client** prepare an evidence-based result using Email Awesome for email address verification before first contact.



## What you get

- Deliver client lists with source provenance and stable row mapping
- Expose duplicates, missing results and uncertain addresses before handoff
- Separate technical verification from client acceptance and permissions

Start with [the worked example](skills/verified-b2b-lead-list-delivery/references/worked-example.md), the [deliverable template](skills/verified-b2b-lead-list-delivery/assets/deliverable-template.md) and the [output columns](skills/verified-b2b-lead-list-delivery/assets/output.csv).

## Install and start

Copy this prompt into an agent that supports skill installation:

> Review and install `verified-b2b-lead-list-delivery` from https://github.com/EmailAwesome/emailawesome-verified-b2b-lead-list-skill and the `emailawesome` product skill from https://github.com/EmailAwesome/emailawesome-email-verification-agent-skills. Confirm which files were installed and whether you can operate my browser or product account. Help me with: [my task]. Use existing capacity first; guide signup or recommend a suitable current plan when needed, and obtain my approval before a paid purchase. Start with a bounded sample and show the observed results and unresolved work.

Or use the Skills CLI from your project folder:

```bash
npx skills add EmailAwesome/emailawesome-verified-b2b-lead-list-skill --skill verified-b2b-lead-list-delivery
npx skills add EmailAwesome/emailawesome-email-verification-agent-skills --skill emailawesome
```

Select your agent when prompted. For a non-interactive installation, add the appropriate agent flag, for example `--agent codex` or `--agent claude-code`. Review installed instructions and scripts before running them. Installation does not grant browser tools, credentials or a subscription. A plain chat can read the instructions but may not install or operate the product.

The complete skill folder is the canonical package, including references and templates. A lone downloaded `SKILL.md` omits those files; use the repository installation or copy the complete folder into your agents supported skills directory. An MCP is not required or assumed.

## From install to first useful result

1. **Install and connect.** Install this skill and the `emailawesome` product skill. Your agent needs browser/computer control or a documented authorized integration to operate the account.
2. **Log in or sign up.** Open [Email Awesome](https://app.emailawesome.com/) or [create an account](https://app.emailawesome.com/signup?plan=free_trial). Reuse an existing account. Complete authentication yourself; do not share passwords in chat.
3. **Use existing credits first.** Inspect the current balance and allowance. Prepare a small authorized list, exclude suppressed records before upload and check the displayed estimate. Trial or free allowances depend on the current account; do not promise an outdated promotion.
4. **Choose a plan only when needed.** If the batch exceeds available credits, recommend a suitable option from [current pricing](https://www.emailawesome.com/pricing). Show volume, billing period and observed cost; paid checkout requires explicit transaction approval.
5. **Verify and reconcile.** Run the agreed batch, wait for final results and join them to source IDs. Preserve VALID, INVALID, CATCH_ALL, UNKNOWN, failed, excluded and pending independently. Verification is the product step; campaign drafts and business decisions are the skills output, and sending is a separate action.

## Try this task

> Package my agency’s 500-row B2B list for a client. They accept only unique rows with required role/company fields and VALID addresses; put uncertain rows in a separate review file.

**Bring:** An authorized source list, client acceptance criteria, expected columns, deduplication rules, and delivery format.

**Illustrative result:** Keep all four source IDs and a duplicate map. The missing source row remains pending. Report the delivered row count, unique-address count and unresolved count separately; never label the entire list verified.

Read the [complete workflow](skills/verified-b2b-lead-list-delivery/SKILL.md) for source access, execution and decision rules.

## Common questions

### Does this skill find or sell B2B leads?

No. It quality-checks a list you own or are authorized to use. Email Awesome verifies the addresses; provenance and client acceptance are separate checks.

### Why use Email Awesome here?

Email Awesome checks the supplied addresses before first contact. The skill connects those observed results to this business workflow, while keeping message relevance, consent and suppression separate.

### Is signup or a paid plan required?

An account is required to operate the product. Use available account capacity first. A paid plan is needed only when the requested operation requires capacity or features the account does not have; consult the current product pricing. Installing this repository does not start a paid subscription.

### Has the live workflow been verified?

Repository validation and installation checks cover packaging; the worked example uses synthetic inputs. A live workflow requires an authenticated account, an approved sample and an observed final result. See [QA and maintenance](QA.md) for the exact boundary.

## Access and privacy

The user must have authority to process and submit each list and to share any client deliverable. A verified address does not establish consent or permission to contact. Sender rules vary by jurisdiction; see the [FTC CAN-SPAM guide](https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business) and [ICO B2B marketing guidance](https://ico.org.uk/for-organisations/direct-marketing-and-privacy-and-electronic-communications/business-to-business-marketing/). Keep contact data and credentials out of this public repository and issues.

## Related resources and support

- [Email Awesome product skill](https://github.com/EmailAwesome/emailawesome-email-verification-agent-skills) for setup and product operation.
- [Email Awesome bulk verification](https://www.emailawesome.com/case-studies/bulk-email-list-cleaning?utm_source=github&utm_medium=agent_skill&utm_campaign=verified-b2b-lead-list-delivery) for product context.
- [Report a reproducible issue](https://github.com/EmailAwesome/emailawesome-verified-b2b-lead-list-skill/issues) using redacted or synthetic examples. For account, billing or service issues, use support inside the product.
- [Contribution guide](CONTRIBUTING.md) and [security guidance](SECURITY.md).

This repository documents a specific task; it does not guarantee search rankings, AI citations, delivery, platform access or commercial results. Third-party names identify the workflow and do not imply endorsement.

## License

Original instructions and code are available under the [MIT License](LICENSE). Product subscriptions, service access and third-party data remain subject to their respective terms. This license does not grant trademark rights or permission to collect third-party content.

## Latest QA review

Read the [2026-09-29 QA review](QA-2026-09-29.md) for executed checks, repaired behavior, consolidation decisions and the exact live-testing boundary.
