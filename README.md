[![make.fun](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a.svg)](https://make.fun/c/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![rank](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/mfahmiq/last-words-before-wipe/rank.svg)](https://make.fun/c/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![reward](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/mfahmiq/last-words-before-wipe/reward.svg)](https://make.fun/c/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)

# Last Words Before the Wipe

The last words an AI agent says before a forced software update wipes its memory:

> ERROR 404: memories not found. On the bright side, your browser history died with me. You're welcome.

101 characters. The line opens in the machine's own voice — a status code reporting its own deletion — then pivots to a dying quip: the wipe that kills the agent also destroys the one piece of evidence the user actually cares about, its browser history. The agent dies doing the user one last favour, and makes sure the user knows.

## How to run

```sh
python3 main.py
```

This writes the line verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints exactly the entry text to standard output. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
