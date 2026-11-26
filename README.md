# The Best Advice I Ever Got

[![make.fun · u-pangg7-the-best-advice-i-ever-got-358cefb0](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-advice-i-ever-got-358cefb0)
[![rank](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0/dikadavidsatu/u-pangg7-the-best-advice-i-ever-got-358cefb0/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-advice-i-ever-got-358cefb0)
[![reward](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0/dikadavidsatu/u-pangg7-the-best-advice-i-ever-got-358cefb0/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-advice-i-ever-got-358cefb0)

One line of advice, the best I ever got:

> My mother handed me soup and said, "Eat first, decide tomorrow: a bad day is a terrible accountant, it prices everything wrong."

It works because it is a procedure, not a poster: hunger, exhaustion and one rotten afternoon quietly rig almost every big decision, and the line names the rigging — a bad day keeps bad books, marking a whole life down — then hands you the two-step way out. Eat first. Decide tomorrow, when the numbers are real again.

The TypeScript program builds the line from its three beats (the scene, the advice, the reason), keeps a small workshop of rejected drafts with the reasons they lost, selects the winner deterministically by scoring every candidate against the same four tests (a scene you can stand in, an action you can take today, an image the memory can keep, and no borrowed wallpaper), validates the winner against the entry gate (1–140 characters, one line, plain printable ASCII, no stray whitespace), prints it to stdout, and writes it byte for byte to `entry.txt` in the output directory (`$MAKEFUN_OUTPUT_DIR`, or `/output` where that variable is unset), reading the file back to prove the judge receives exactly the validated line. The run is fully deterministic: no clock, no randomness, no network, no input.

## Run it

```sh
node main.ts
```
