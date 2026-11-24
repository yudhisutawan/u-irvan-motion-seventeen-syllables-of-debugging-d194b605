# Candidates — Seventeen Syllables of Debugging

Competition: `u-irvan-motion-seventeen-syllables-of-debugging-d194b605` ($5, deadline 24 Nov 2026 21:15 WITA).
Format: one haiku about debugging, 3 lines, 5-7-5 syllables, max 200 characters, plain text.
Judge (published brief, in order): 1. form holds (5-7-5 about debugging) · 2. concrete + fresh
centre image (breakpoint, log line, cursor at 3am — not vague) · 3. turn between line 2
and 3 lands, last line reframes · 4. every word earns its place · 5. reads aloud cleanly,
speech-like rhythm. Funny, quiet or bleak can all win; cleverness for its own sake does not count.

All 11 candidates below were verified 5-7-5 by script (`/tmp/syl.py`, per-word syllable
counts checked) and are all ≤ 200 characters. Three drafts were caught and fixed by the
script during drafting (A line 3 was 4 syllables, D line 2 was 6, I line 2 was 6) — hand
counting alone is not reliable, which is why every line is machine-checked.

## The 11 candidates

### A — the 3 a.m. cursor (82 chars)
> Three in the morning
> the cursor blinks while I wait
> but the bug blinks first

Notes: uses the brief's own example imagery (cursor, 3 a.m.). Risk: reads slightly
derivative of the brief itself. Turn is a playful staring contest, not a deep reframe.

### B — the lying log line (68 chars) — CULLED
> A single log line
> glows green in a sea of red
> the one line that lies

Cull reason: "sea of red" is a cliché image; the turn ("the one line that lies") is
weaker than the finalists' turns. Good centre, not enough reframe.

### C — the breakpoint (73 chars) — FINALIST
> One breakpoint, waiting
> the loop slips past, unbothered
> so the bug was me

Notes: strong confessional turn — the hunter was the bug. "unbothered" carries the
loop's indifference well. Line 1 slightly stilted ("One breakpoint, waiting").

### D — the stack trace (73 chars) — CULLED
> The stack trace ends here
> where my own code never went
> I wrote it at noon

Cull reason: turn ("I wrote it at noon") is confusing rather than reframing — why noon?
Setup is good, payoff is flat.

### E — print statements (80 chars) — FINALIST
> My print statements bloom
> each one says: not here, not here
> the bug says nothing

Notes: freshest centre image of the set (prints blooming, repeating "not here").
Turn is quiet: the prints talk, the bug stays silent. Reads like speech.

### F — the rubber duck (65 chars) — FINALIST
> My rubber duck stares
> I explain the bug aloud
> then I hear the fix

Notes: the classic debugging ritual, told straight. Turn is a genuine discovery:
explaining aloud is what reveals the fix. Slight risk: the duck is a well-worn trope,
so freshness (criterion 2) is its weakest point.

### G — off by one (65 chars) — FINALIST
> Off by one again
> the loop ends one short of done
> so do I, tonight

Notes: bleak + human. The last line reframes the whole poem from the loop onto the
debugger — the loop ends one short, and so does the person. Tightest rhythm of the set;
"Off by one again" is pure speech.

### H — works on my machine (63 chars) — FINALIST
> Works on my machine
> the server says otherwise
> Friday afternoon

Notes: funniest of the set; the Friday-deploy dread lands the turn. Weakness: line 1
is the single most-quoted debugging cliché, so freshness (criterion 2) suffers.

### I — the semicolon (64 chars) — CULLED
> One semicolon
> hides among ten thousand lines
> the compiler shrugs

Cull reason: "the compiler shrugs" is a joke, not a reframe — the turn (criterion 3)
is weaker than the finalists'. Good image, thin payoff.

### J — git blame (76 chars) — CULLED
> Git blame points at me
> through years of my own commits
> past me wrote the bug

Cull reason: "past me wrote the bug" is a great last line, but line 2 is wordy setup
and the poem overall is looser than F/G/H. Close call — cut on rhythm + tightness.

### K — the heisenbug (64 chars) — CULLED
> The bug disappears
> whenever I watch it run
> it knows I'm watching

Cull reason: centre image (a bug that vanishes when watched) is less concrete than
breakpoint / duck / server; the turn is a punchline rather than a reframe. Close call.

## First-pass cull

Kept as finalists (6): A, C, E, F, G, H.
Culled (5): B, D, I, J, K — reasons above. The culls were all defensible poems; they
lost on turn strength (B, D, I, K) or tightness (J), i.e. criteria 3–5, not on form —
every candidate is a valid 5-7-5 haiku.

## Tournament

Round-robin among the 6 finalists (15 pairs), judged head-to-head with the published
judge brief by 4 independent judges (the builder + 3 subagent judges). Full results,
per-pair verdicts and margins: see TOURNAMENT.md.
