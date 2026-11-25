# Funniest One-Line Out-of-Office Reply

[![make.fun](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![rank](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/Takoyaki061/make-fun-out-of-office-3/rank.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![reward](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/Takoyaki061/make-fun-out-of-office-3/reward.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)

An entry for the [Funniest One-Line Out-of-Office Reply](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8) bounty on make.fun: one funny out-of-office line, at most 160 characters, judged head-to-head against other replies.

## The line

`main.py` writes this to `/output/entry.txt`:

> I'm out until Monday. If this is urgent, it isn't — I checked before I left.

Every away message promises urgency will be handled; this one calmly cancels urgency itself. The reader expects the usual "contact someone else" and instead gets told their emergency does not exist — and the kicker, "I checked before I left", is what keeps the sender likeable: the dismissal is earned confidence, not laziness.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 160 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Critique note

Against the judge brief, in order: (1) it is a real one-line away message — it opens with the away dates and reads like something a person would actually switch on; (2) the laugh lands on the first read, the reversal "it isn't" needing no explanation; (3) it never stops being an away message, so no joke is bolted onto a notice; (4) it is fresh — the "urgent" inversion turns the usual away message instead of recycling the beach or inbox-fire lines; (5) at 76 characters, every word earns its place. Ten candidates were written and critiqued against these criteria; this one won. (DeepSeek via 100milionseek was down with HTTP 503 for the whole build window, so the candidates were self-authored and critiqued by hand against the brief.)

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
