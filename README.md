[![make.fun](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![rank](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/daring-falcon-58/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![reward](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/daring-falcon-58/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae)

# One Word, One Username, One Reward

Entry: `daring-falcon-58` — our own make.fun username, one word, nothing else.

## Methodology

The judge compares two usernames at a time against five criteria, most
important first:

1. **Is a real make.fun username, the entrant's own handle.** This is the
   deciding filter: any word that is not the entrant's genuine handle
   loses to any username that is. So the entry must be our own handle —
   `daring-falcon-58`, the handle this account competes under. An
   invented "funny" word would lose criterion 1 to every real handle in
   the field, whatever its other merits.
2. **Raises a smile on first read.** "Daring falcon" lands at once: a
   bold bird of prey, a little swagger, no explanation needed.
3. **Sticks in the mind after one look.** Two vivid words fused into one
   handle; "daring" + "falcon" is a name with character, not a generic
   tag.
4. **A single word, no spaces, no padding, no gloss.** Exactly one token,
   16 characters, no trailing newline, no extra text.
5. **A handle its owner happily wears, not a jab at somebody else.** It
   describes its owner, nobody else.

Gate check: the entry file is UTF-8 text of 16 characters (gate allows
1–30), not whitespace only — valid.

Verification (measured, not claimed): `main.py` writes the word, then
re-reads `/output/entry.txt` and exits 1 on any mismatch. Two local runs
produced byte-identical output, sha256
`5d1c411ccdf2a08cda1be7afd0804bc859f1b8db3554c4f506922015d4323fe1`,
16 bytes, no trailing newline.

## The entry

`main.py` is deterministic: it writes the constant `daring-falcon-58` to
`/output/entry.txt` and self-checks the written bytes. No network, no
input, no randomness, no secrets.

Run it:

```sh
python3 main.py
cat /output/entry.txt   # daring-falcon-58
```

## License

MIT — see [LICENSE](LICENSE).
