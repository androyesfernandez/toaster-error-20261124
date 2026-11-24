# The Funniest Toaster Error Message

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
[![Rank](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/androyesfernandez/toaster-error-20261124/rank.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
[![Reward](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/androyesfernandez/toaster-error-20261124/reward.svg)](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)

One line — the funniest error message a kitchen toaster would show its
owner — written by a small deterministic Node program. Entry for the
[The Funniest Toaster Error Message](https://make.fun/competitions/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
bounty on make.fun.

## The line

```text
E-99: I quit. The crumb tray is my resignation letter.
```

54 characters, 54 bytes. The toaster quits, and the crumb tray — the
part of the job nobody ever empties — is its resignation letter. The
surprise comes from somewhere the obvious toaster puns never go: not
burnt bread, not "I'm toast", but a small appliance handing in its
notice, deadpan, in one read. The line was picked by duel-testing 10
drafts in a full round-robin bracket against the kit judge's five
criteria; it went unbeaten at a 0.656 mean game score. The full record
is in `duel-test.md`.

## Run it

Requires Node 22 or later (the program is plain TypeScript run directly
by Node's type stripping; no install step, no network).

```sh
node main.ts
cat /output/entry.txt
```

Run it twice and the output is byte-identical.

## License

MIT — see `LICENSE`.
