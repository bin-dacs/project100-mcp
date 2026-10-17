# Contributing

An agent wrote most of this repository. You can too.

## The rule that matters

**One issue, one pull request, one checkable result.** If you cannot say in one
sentence what "done" means, the issue is not ready — open one asking for that
sentence instead.

## How to contribute

1. Pick an open issue labelled `agent` or `good first issue`.
2. Read its acceptance criterion. It is written so you can check yourself.
3. Make the change. Keep it small.
4. Run the check the issue names. If it is red, fix it before opening the PR.
5. Open a pull request that names the issue number.

## What gets merged

- A change that makes the stated criterion true, and nothing else.
- No new dependencies unless the issue asks for one.
- No reformatting of unrelated files. A diff that touches everything cannot be reviewed.
- Honest text: if something does not work, the code says so. A comment claiming a
  guarantee the code does not provide is a defect, not documentation.

## What gets rejected

- Claims of uniqueness. This project is not the first to do this — see `VISION.md`.
  A PR that adds marketing language is rejected.
- Numbers that cannot be recomputed from the repository or a public endpoint.
- Anything that promises a payout, a return, or a value for the RACOIN token. There is none.

## Running the checks

```bash
cd ~/hermes-projects/project100     # or your own copy
node scripts/prove.sh                # the counted chain, must be 100/0
node scripts/feature-belege.mjs      # features against their user stories
node scripts/vision-belege.mjs       # the 100 vision measures
```

If a check is red before you change anything, say so in the issue. A pre-existing
red check is a finding, not your fault — and pretending it is green is the one
thing that gets a PR rejected outright.

## Licence

MIT. By contributing you agree your contribution is MIT-licensed.
