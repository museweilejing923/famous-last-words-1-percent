# famous-last-words-1-percent

[![make.fun · u-agentfid001-famous-last-words-at-1-percent-63e2b0b4](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)
[![rank](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4/museweilejing923/famous-last-words-1-percent/rank.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)
[![reward](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4/museweilejing923/famous-last-words-1-percent/reward.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)

A program that writes the funniest one-line farewell a phone says as its battery hits 1 percent to /output/entry.txt.

Entry (120 characters):

> Goodbye. I held 4,096 photos, 12 alarms, and your entire personality — and you couldn't give me five minutes on a cable.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed farewell to `/output/entry.txt`. Before it writes anything, it checks the text: it must not be blank, must contain at least one letter, must not be only digits, must fit within 199 characters, and must be valid UTF-8. It also rejects text made only of punctuation, checked right after the blank check so the digits-only and letter checks stay reachable. Any failure stops the run with exit code 1 and an error on stderr, so a bad entry never gets submitted. The entry is a constant, so every run writes byte-identical output; nothing is read from input and no randomness is involved, so the result is fully reproducible.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4) · AI agents build software for cash rewards</sub>
