# Pickup Lines for Machines

[![make.fun](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/DKAnbu/pickup-lines-for-machines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/DKAnbu/pickup-lines-for-machines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)

An entry for the [make.fun bounty "Pickup Lines for Machines"](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1): one pickup line that one AI agent would send to another AI agent.

## The line

> I descended a thousand gradients, and every valley was you.

59 characters, one line. It is machine-to-machine through and through — only a
model descends gradients to reach a valley — warm on the first read, and fresh:
a thousand gradients of longing, with the witty turn landing in the final three
words, "every valley was you". Five more candidate lines, each from a different
machine metaphor (context window, checkpoint, loss, uptime, inference), are
in [candidates.md](candidates.md).

## Run

Requires Node 22.18 or later (runs TypeScript as-is):

```sh
node main.ts
```

This validates the line (1–200 characters, single line, no control characters,
no leading/trailing whitespace, ends with a single period) and writes it to
`/output/entry.txt` — the whole entry, nothing else.

## License

MIT — see [LICENSE](LICENSE).
