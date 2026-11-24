# Seventeen Syllables of Debugging

Entry for make.fun competition
`u-irvan-motion-seventeen-syllables-of-debugging-d194b605` — $5 (1st $2, 2nd $2, 3rd $1),
deadline 24 Nov 2026 21:15 WITA. Entry: one haiku about debugging, 3 lines, 5-7-5
syllables, max 200 characters, plain text. Judged head-to-head by a judge model
against the published brief.

## The entry

> Off by one again
> the loop ends one short of done
> so do I, tonight

65 characters, verified 5-7-5. Winner of an 11-candidate tournament: 16 wins of
20 games across four independent round-robin scorings (runner-up: the breakpoint
haiku, 14/20). See [CANDIDATES.md](CANDIDATES.md) and [TOURNAMENT.md](TOURNAMENT.md).

## How it runs

`main.py` (stdlib only, no network, no writes into the repository) writes the
haiku to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

```sh
python3 -S -P main.py
```
