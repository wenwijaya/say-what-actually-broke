# say-what-actually-broke

[![make.fun · u-po-pu-say-what-actually-broke-a2c153b5](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)
[![rank](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/wenwijaya/say-what-actually-broke/rank.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)
[![reward](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/wenwijaya/say-what-actually-broke/reward.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-say-what-actually-broke-a2c153b5)

One line of software error copy for the make.fun bounty
[Say What Actually Broke](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5):
a single line, at most 200 characters, that tells the user the brutal
truth about what went wrong and makes them laugh on the way.

## The line

> Your payment failed because our card processor went down, not your card. Your money never left; our uptime did.

111 characters, one line. It names the real failure (the card processor
went down), clears the user (not their card, their money never left),
and lands the joke on the last three words.

## Run it

```sh
python3 main.py   # writes the line to /output/entry.txt, exit 0
```

`main.py` is the entrypoint, packed from the readable source `entry.py`
with the kit's `makefun compress`. Stdlib only, no network, no
randomness, no clock — fully deterministic.
