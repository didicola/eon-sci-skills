# eon-sci-skills

Curated extract of **16 skills** from
[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
(49k+ stars, 177 skills total, MIT) — selected and mapped to the EON
sovereign AGI family's actual roles. No upstream code was modified; files are
verbatim under `UPSTREAM-LICENSE.md` (MIT).

Full upstream is 474 MB; this extract is ~3.6 MB. For the rest, use the
upstream repo (they are all excellent — this is a storage-motivated cut, not
a quality judgment).

## Selection → family role map

| Skill | EON role it strengthens |
|---|---|
| literature-review | Researcher |
| paper-lookup | Researcher (arxiv/pubmed/crossref/openalex lanes) |
| research-lookup | Researcher (manuscript packets) |
| scientific-critical-thinking | Critic / verifier (biases, fallacies, evidence hierarchy) |
| hypothesis-generation | Subconscious / planner (falsification, prediction matrices) |
| statistical-analysis | Markets / data lanes (tests, power, bayesian) |
| market-research-reports | Markets-Agent (sizing, competitor matrices, forecast sensitivity) |
| scientific-writing | Summarizer / Archivist (scaffolds, consistency, claim audits) |
| markdown-mermaid-writing | Graphify (24 mermaid diagram families + style guides) |
| scientific-visualization | Presentation-Agent (publication figures, palettes, mpl styles) |
| infographics | Presentation-Agent (type catalog + AI generator) |
| pptx-posters | Presentation-Agent (poster pipeline, pptx security checks) |
| citation-management | Archivist (doi/bibtex/pubmed/scholar search + validation) |
| peer-review | Critic (review scaffold, claim-evidence validation) |
| generate-image | Imagine lanes (model catalog + generator script) |
| markitdown | Tools-Agent (doc→markdown conversion, batch) |

## Use

Standard Agent-Skills layout: copy any `skills/<name>/` directory into
`~/.config/opencode/skills/` (or the agent's skills root) and the model
loads `SKILL.md` when the task matches. Scripts are stdlib-python where
possible; some reference optional scientific packages — read each
`SKILL.md` "dependencies" section before running.

## Pointer (family)

Local pointer skill for EON phones/nodes: `eon-sci` (see repo instructions
in the family arch). Registry of what is curated here is also mirrored in
the EON skill cortex notes.

---
Upstream: https://github.com/K-Dense-AI/scientific-agent-skills · MIT ·
retrieved 2026-10-15.
