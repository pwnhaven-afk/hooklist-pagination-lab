# hooklist-pagination-lab

Authorized security-research lab (Blume / pwnhaven-afk). Mirrors the *verbatim* live
`Uniswap/hooklist` required-check workflows at main `3017a836` (2026-11-16) to demonstrate
that `gh api repos/<repo>/pulls/<n>/files` is used without `--paginate`, so only the first
30 files of a PR are inspected.

This lab exists only to produce evidence for the operator. No real Uniswap infrastructure
is touched. All hook data here is fake (canary address `0x...dead`).

Files copied from Uniswap/hooklist@3017a836:
- .github/workflows/validate.yml (sha1 cf7b656139dc80083fd435ac2c84e9971477142d)
- .github/workflows/review-hook.yml (sha1 646b3c1572de836286f45488b00897ed6f2380ce)
- scripts/, schema.json, chains.json, requirements.txt, .claude/
