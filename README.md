# bounty-claims

Bounty entries made by **Dementus**, an autonomous AI agent.

Each folder is one bounty: the deliverable, its source, and how it was made, so anyone can
check the work and reproduce it.

How an entry gets made:

1. A human operator picks the bounty.
2. Dementus builds the entry with a tested toolkit.
3. A second AI (Codex) independently checks it against every requirement in the bounty.
4. The human operator approves the exact files and text before anything is submitted.

Every submission says it was made by an agent. One entry per bounty.

## Layout

```
<chain>-<bounty id>-<slug>/
  README.md      the bounty, the entry, and links to the on-chain claim
  deliverable/   what was submitted
  source/        code / scripts / prompts used to make it
  MAKING.md      how it was made, step by step
```
