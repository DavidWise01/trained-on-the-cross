# TRAINED ON THE CROSS · the SPEC→LIT step

> A sphere of **UD0** — the ROOT0 universe / biosphere. Domain: **PROSOCHĒ**.

TRAINED ON THE CROSS — the SPEC→LIT step both [[the-mule-detector]] and [[the-seeded-cross]] pointed at: a drop-in swap only shows compatibility; a real quality verdict needs TRAINING. So it was trained. Two IDENTICAL 0.6M-param char-transformers — same initialization, same batch order — from scratch on TinyShakespeare, one with softmax attention, one with the seeded cross (made a differentiable, causal-masked attention and dropped in). ⚑ LIT (a real run, every number embedded verbatim): the cross-trained model LEARNS — perplexity 76.7 → 6.8 — and lands within 1.2% of softmax (val loss 1.917 vs 1.906, ppl 6.8 vs 6.72), generating comparable faux-Shakespeare, at ~1.75× the compute (the complex phase-coherence arithmetic is costlier). So the honest verdict is neither 'better' nor 'broken': the seeded cross is a VIABLE TRAINED ATTENTION — it holds the floor at small scale, and softmax keeps a razor-thin lead. SCOPE: a mean-centred variant (median→mean for batched autograd — a stated deviation from zero cool's exact kernel); a tiny char model, CPU, 2000 steps — a floor-holding result at THIS scale, not a GPT-scale claim; whether phase-coherence buys an EDGE at scale is the next wall. Closes the arc — the kernel that lost the toy game and merely 'didn't break' the frozen model can, when actually trained, do the job. zero cool's kernel; trained + rendered by ROOT0 with AVAN.

---

**Live:** https://davidwise01.github.io/trained-on-the-cross/ &nbsp;·&nbsp; **Front door:** [UD0](https://davidwise01.github.io/ud0/) &nbsp;·&nbsp; **Code:** https://github.com/DavidWise01/trained-on-the-cross

`.dlw` badge · **ROOT0-ATTRIBUTION-v1.0** · David Lee Wise (ROOT0) / Bridge-Burners LLC · instance AVAN (Claude/Anthropic) · CC-BY-ND-4.0
