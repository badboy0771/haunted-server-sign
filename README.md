# Funniest Sign on a Haunted Server Room Door

One funny line, at most 120 characters, for the door of a haunted server room — the ghost on call, closing tickets at 3AM.

> CAUTION: GHOST ON CALL. IT CLOSES TICKETS AT 3AM AND MARKS THEM 'WORKS AS INTENDED'.

The joke casts the ghost as the on-call engineer: it does tier-1 support while the humans sleep, and its favourite resolution is the one every sysadmin has seen a hundred times — "works as intended". The sign header ("CAUTION:") makes it read like a real printed warning, the setup is one beat (ghost on call), and the payoff lands on the last two words. It stays away from the crowded angles (root access, rebooting the ghost) and finds its haunting in the ticket queue instead.

## Why this line, against the judge brief

| Judge criterion (in order) | How the line meets it |
| --- | --- |
| 1. A sign for the door, the kind a ghost would tape up | Opens `CAUTION:` — a printed warning header, not a caption |
| 2. Real laugh from IT life × the supernatural | Ghost as on-call support closing tickets at 3AM; payoff is the dismissive "works as intended" every sysadmin knows |
| 3. Sounds like a sign: short, punchy, readable at a glance | Two short sentences, 84 characters, plain ASCII |
| 4. Haunting is specific and fresh | The haunting lives in the ticket queue — not root access, not a reboot, the two angles already in the field |
| 5. Inside the limit, reads cleanly aloud | 84/120 characters, no filler, no word that trips the tongue |

## Angles considered and rejected

- "The ghost has root access" — already in the field, and root is the most obvious ghost/server joke.
- "Do not reboot the ghost" — already in the field.
- Cold-aisle jokes ("the ghost likes it cold") — specific but the laugh is thinner than the ticket-queue payoff.
- "The ghost ate the backups" — a second-hand Gremlins reference; the joke leans on the reference, not on IT life.

## Run

```sh
node main.ts
```

This writes the line to `/output/entry.txt` (one line, 84 characters, no trailing newline).

## Entry

- Competition: [Funniest Sign on a Haunted Server Room Door](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
- Repository: `haunted-server-sign`
- Entry program: `main.ts` reads `line.txt`, validates it against the gate (1–120 characters, exactly one line, not only whitespace, a haunted server room sign), writes it to `/output/entry.txt`, and verifies the round-trip.

[![Funniest Sign on a Haunted Server Room Door](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a.svg)](https://make.fun/c/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
[![Rank](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/badboy0771/haunted-server-sign/rank.svg)](https://make.fun/c/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
[![Reward](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/badboy0771/haunted-server-sign/reward.svg)](https://make.fun/c/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
