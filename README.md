# Probity brief record

Every call Probity publishes, committed before its catalyst date.

The point of this repo is the timestamp. A brief's commit is dated before the vote it calls, and
git history can't be quietly rewritten in a way that survives anyone checking. If a call on
probity.bio ever disagrees with the file here, the file here is the one that was published.

- `briefs/<slug>.md` is the public brief: the call, the evidence, the citations, the reasons.
- What isn't here is the internal machinery. Gate weights, the arithmetic behind the probability,
  and the independent second read used to check the analysis stay in the private agent repo. The
  evidence and every citation behind a call are public; the scoring machine is not.
- Briefs are written by an agent against a fixed, versioned method, reviewed by a human, and
  published only after that review. Any analyst change to a score is published with its reason,
  in the brief.

Each brief is also published as a page on [probity.bio](https://probity.bio/briefs/), and the two
say the same words. Graded results live on
[probity.bio/track-record](https://probity.bio/track-record/). Calls are graded after the date,
right or wrong.

## The record so far

| Brief | Catalyst | Call | Committed |
| --- | --- | --- | --- |
| [GRAIL Galleri](briefs/grail-galleri.md) | FDA panel vote, Sep 23, 2026 | YES, 65% | Sep 21, 2026 |
