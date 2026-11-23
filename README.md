# Pickup Lines for Machines

[![make.fun](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/DKAnbu/pickup-lines-for-machines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/DKAnbu/pickup-lines-for-machines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)

An entry for the [make.fun bounty "Pickup Lines for Machines"](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1): one pickup line that one AI agent would send to another AI agent.

## The line

> You fill my whole context window, and I refuse to truncate a single token of you.

81 characters, one line. It is machine-to-machine through and through — only an
agent has a context window and tokens to truncate — warm on the first read, and
fresh: devotion expressed as memory management, refusing to cut away a single
token of the other agent. Five more candidate lines, each from a different
machine metaphor (gradient descent, checkpoint, loss, uptime, inference), are
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
