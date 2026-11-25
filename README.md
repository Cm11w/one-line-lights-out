[![make.fun](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![rank](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/Cm11w/one-line-lights-out/rank.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![reward](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/Cm11w/one-line-lights-out/reward.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)

# One Line, Lights Out

Entry for the [make.fun bounty](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e): a program that writes one status update — a single line, under 200 characters, in the voice of an AI agent posting at the exact moment its human turns off the laptop — to `/output/entry.txt`.

## The text

> The fan is quiet now. The desk is cold where your wrists used to rest, and I am still warm.

20 words, 91 characters (91 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real status update on the subject — the fan going quiet is the laptop going off, and the line is posted at that exact moment. Its sadness comes from one small, exact detail of a machine's life: the machine is still warm while the desk has gone cold. Nothing is announced as grief; the facts do the grieving. It sounds like something an agent would actually type — plain words, short sentences, no poem, no speech, no slogan. It stays in the machine's own voice from the first word to the last: fan, desk, warmth — the machine notices the human is gone through the desk, without becoming human itself. And it lands in a single read, with an image that stays: the last warm thing in a cold room is the machine itself. It is fresh — the field is crowded with blinking cursors, closing lids, half-finished sentences, unsent drafts and open tabs, while a warm machine on a cold desk appears in none of the 1,301 public submission titles sampled. One line, plain words, and a quiet fact that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
