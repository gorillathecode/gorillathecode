# Contribution notes

This page distinguishes public Git attribution from the broader work of a project team. Commit attribution documents a contribution; it does not establish sole authorship or ownership of later revisions.

## Interactive Wallet

**Context:** university SSI wallet team project. The overall agent architecture and current integrated product are team work.

| My attributable contribution | Public evidence |
| --- | --- |
| Initial Flutter interface: screens, models, theme and mock-data flows | [Commit 7d841e7](https://github.com/interactive-wallet/interactive-wallet/commit/7d841e732cee4cdc96425eab5b2a25bb6ffb68c3) |
| Revocation-flow changes across issuer, holder and verifier, including tails-file support and a revocation script | [Commit 868a95b](https://github.com/interactive-wallet/interactive-wallet/commit/868a95b1ba5e4b46a24d3fbea567c9c4864bf891) |
| RabbitMQ revocation notification forwarded through SSE to the Flutter audit log | [Commit 3dfc38a](https://github.com/interactive-wallet/interactive-wallet/commit/3dfc38acf0b791e37a43d28ae65d3c7cc43220f2), [merged PR #15](https://github.com/interactive-wallet/interactive-wallet/pull/15) |

The initial interface used mock data. Subsequent API integration, fixes and extensions also have contributions from other team members. The notification commit credits Claude as a co-author.

## WebFAQ

**Context:** TU Berlin multilingual FAQ retrieval team project. Extraction, filtering, labeling, training and evaluation are presented as team deliverables.

Publicly attributable contributions under my GitHub account:
- [README update](https://github.com/gorillathecode/WebFAQ/commit/6563745bd65140aa546bbde723f26b0aa647acb5).
- [Removal of a team-context file](https://github.com/gorillathecode/WebFAQ/commit/713ee66a8fc9c2fe2d72d158d1f552ab470357c0).
- [Upstream PR #1: dependency cleanup](https://github.com/lsdipro-webfaq/WebFAQ/pull/1), including the NumPy upper bound and removal of duplicate dependency entries. **Open, not merged when these notes were prepared.**

These records do not establish personal authorship of the training or retrieval implementation. No personal implementation claim is made for work that cannot be attributed from the linked records.

## TutorAI

The [current team repository](https://github.com/Programmierpraktikum-MVA/tutor_ai) is the reference for the project; my older fork is not the current implementation.

[Commits attributed to my account](https://github.com/Programmierpraktikum-MVA/tutor_ai/commits?author=gorillathecode) establish historical participation. They do not establish ownership of the current RAG architecture or all current features.

## Personal repositories

**Fino** is my financial-software prototype. Its README links to the implemented client, persistence and server-side integration boundaries.

**Miele TextilExpert** is a workshop prototype published in my repository. Its [implementation commit](https://github.com/gorillathecode/miele-textilexpert/commit/8f873655da508d2ff695043c527db934f064e969) is attributed to my account and credits AI coding assistance. The prototype is not presented as a production Miele product.

**Claude Engineering Skills** packages existing local workflows. Examples illustrate their intended use; they are not benchmark results.

Prepared on 2026-10-15. Follow the linked PRs for their current status.
