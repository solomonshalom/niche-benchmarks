# In Defense of Niche Benchmarks

**Why the Long Tail of LLM Evaluation Matters** — a position paper arguing that the proliferation of domain-specific, industry-vertical, and indie/informal LLM benchmarks (SkateBench, SnitchBench, PIF-Bench, MedQA, LegalBench, FinBen, etc.) is not fragmentation to be cleaned up but a structurally necessary correction to the saturation, contamination, and Goodhart-style overoptimization of general-capability leaderboards.

- **Paper (LaTeX source):** [`paper/niche_benchmarks.tex`](./paper/niche_benchmarks.tex)
- **Author:** Solomon Shalom Lijo ([Rōmy](https://getromy.app))
- **Contact:** solomon@getromy.app
- **License:** [CC BY 4.0](./LICENSE)

## Summary

General-purpose LLM benchmarks (MMLU, HumanEval, GPQA Diamond) have entered a regime in which leading models cluster within 2–4 percentage points of one another, with substantial evidence of training-data contamination undermining what gaps remain. The community's response has been a rapidly growing tail of niche benchmarks. The dominant framing in recent literature treats this proliferation as a problem. This paper argues the opposite: niche benchmarks generate value in two directions at once.

For practitioners, they make model selection a tractable, evidence-based decision tied to a specific deployment context. For frontier laboratories, they provide discriminating signal precisely where general benchmarks no longer separate models, and they surface failure modes (geographic recall gaps, temporal displacement of facts, edge-case adaptation, sensitive-topic handling) that aggregate accuracy metrics obscure.

The paper proposes:

1. A **three-tier taxonomy** of niche benchmarks — academic-formal, industry-vertical, and indie-informal — and argues each tier contributes a distinct, complementary signal.
2. A **design playbook** of seven principles for constructing high-signal niche benchmarks (domain-grounded dimensions, verifiable ground truth, impact-weighted scoring, edge-case inclusion, temporal freshness, public methodology, practitioner-led design).
3. **Three short benchmark vignettes** — SkateBench (Tier 3), SnitchBench (Tier 3), PIF-Bench (Tier 2) — illustrating how benchmarks across radically different scopes and methodological styles each surface failure modes invisible to general evaluation.
4. **Engagement with the standard counterarguments** — fragmentation, quality variance, evaluator conflict, cultural bias — and arguments that the appropriate response is meta-infrastructure investment (benchmark cards, registries, portfolio-level evaluation) rather than supply restriction.

## Related work by the same author

- [PIF-Bench](https://github.com/getromy-app/pif-bench) — Prospect Intelligence Fidelity Benchmark, the Tier 2 industry-vertical benchmark used as one of the three case studies in this paper.

## Citation

```bibtex
@misc{shalomlijo2026niche,
  author       = {Shalom Lijo, Solomon},
  title        = {In Defense of Niche Benchmarks: Why the Long Tail of LLM Evaluation Matters},
  year         = {2026},
  howpublished = {arXiv preprint},
  note         = {Forthcoming. Source available at \url{https://github.com/solomonshalom/niche-benchmarks}}
}
```
