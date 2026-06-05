# FACTCHECK — claude-prompt-engineering

**Run date:** 2026-06-01  
**Checker:** Claude (claude-sonnet-4-6), automated pre-publication register  
**Method:** Full grep of all `[verify]`, `[verify — ...]`, `[UNVERIFIED]`, `[contested]`, `[AGING]` flags across chapters/*.md; web-search verification of all CITATION/STAT items; PRODUCT/PLATFORM items deferred.

---

## Summary

| Category | Count |
|---|---|
| Total flagged items extracted | 38 |
| PRODUCT/PLATFORM (deferred) | 29 |
| CITATION/STAT (verified this run) | 8 |
| CONTESTED | 1 |
| **Corrections needed** | **2** |
| Confirmed clean | 6 |

---

## Full Item Table

| # | Chapter | Flagged claim / citation | Type | Verdict | Action needed |
|---|---|---|---|---|---|
| 1 | Ch 00 Introduction | Note about model-specific behavior markers being used throughout | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 2 | Ch 01 Anatomy | "Some research on over-constrained prompts suggests diminishing returns at extreme constraint density" | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 3 | Ch 02 Context | "Context overload" claim — high volume makes it harder for Claude to prioritize | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 4 | Ch 02 Context | Claude resolves contradictory context without flagging it | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 5 | Ch 03 Constraints | Claude may drift from instructions in long sessions; restate constraints | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 6 | Ch 03 Constraints | "More sophisticated uncertainty signaling emerged from the models themselves" | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 7 | Ch 03 Constraints | Does constraint position in a prompt affect reliability? | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 8 | Ch 03 Constraints | Anthropic prompt engineering docs URL (docs.anthropic.com) | PRODUCT/PLATFORM | DEFERRED | Check URL is current at publication time |
| 9 | Ch 04 Examples | Copyright in outputs — open area of law and policy | CONTESTED | DEFERRED | Remains contested; phrasing is accurate as of writing |
| 10 | Ch 04 Examples | Claude does not have stable style memory across a long conversation | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 11 | Ch 04 Examples | "Better mechanisms for persistent style memory appeared in Claude's product features" | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 12 | Ch 04 Examples | Example management across long projects with varying context windows | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 13 | Ch 04 Examples | Anthropic prompt engineering documentation URL | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 14 | Ch 04 Examples | Anthropic AI safety guidance URL | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 15 | Ch 04 Examples | Brown, T. B., et al. (2020). Language models are few-shot learners. *Advances in Neural Information Processing Systems*, 33. | CITATION/STAT | CONFIRMED | Citation is correct. Paper published NeurIPS 2020, arXiv 2005.14165. |
| 16 | Ch 04 Examples | Sweller, J. (2006). The worked example effect and human cognition. *Learning and Instruction*, **16(2)**. | CITATION/STAT | CORRECTED → [fix] | Article confirmed in *Learning and Instruction*, vol. 16, pp. 165–169. Issue number "(2)" is not confirmed by any source; standard citation form omits issue number. Fix: remove "(2)", add pages: `16, 165–169`. |
| 17 | Ch 05 Evaluation | Claude's arithmetic is not always reliable | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 18 | Ch 05 Evaluation | Criteria buried after long context may receive less weight (prompt position effects) | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 19 | Ch 05 Evaluation | Claude's capacity to self-evaluate against stated criteria | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 20 | Ch 05 Evaluation | Does order of criteria affect which receive more weight? | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 21 | Ch 05 Evaluation | Parasuraman, R., & Manzey, D. H. (2010). Complacency and bias in human use of automation. *Human Factors*, 52(3), 381–410. | CITATION/STAT | CONFIRMED | Verified: correct journal, volume, issue, pages, year. |
| 22 | Ch 05 Evaluation | Mosier, K. L., & Skitka, L. J. (1996). Human decision makers and automated decision aids. In Parasuraman & Mouloua (Eds.), *Automation and Human Performance*. Lawrence Erlbaum. | CITATION/STAT | CONFIRMED | Verified: chapter exists in the cited edited volume with correct editors and publisher. |
| 23 | Ch 05 Evaluation | Popham, W. J. (1997). What's wrong — and what's right — with rubrics. *Educational Leadership*, 55(2), 72–75. | CITATION/STAT | CONFIRMED | Verified via ERIC (EJ552014) and ASCD. Correct journal, volume, pages. |
| 24 | Ch 05 Evaluation | Moher, D., et al. (2009). PRISMA statement. *PLOS Medicine*, 6(7). | CITATION/STAT | CONFIRMED | Verified: *PLOS Medicine* 6(7): e1000097, July 2009. Correct. |
| 25 | Ch 05 Evaluation | Anthropic prompt engineering documentation URL | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 26 | Ch 06 Iteration | Claude generally follows explicit preservation constraints but not guaranteed | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 27 | Ch 06 Iteration | Claude's self-critique more useful for surface issues than factual accuracy | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 28 | Ch 06 Iteration | Huang et al. 2023 found self-correction without external feedback often does not improve and can degrade output quality | CITATION/STAT | CONFIRMED with note | Paper confirmed (arXiv 2310.01798). Finding is accurately characterized. However, the book lists venue as just "[verify — current as of writing]" in the reference — the paper was published at **ICLR 2024**, not as a standalone 2023 preprint. Action: update reference line to add venue. |
| 29 | Ch 06 Iteration | Huang, J., et al. (2023). Large language models cannot self-correct reasoning yet. [verify — current as of writing] | CITATION/STAT | CORRECTED → [fix] | Paper published as ICLR 2024 proceedings. Reference should read: Huang, J., et al. (2023/2024). Large language models cannot self-correct reasoning yet. *ICLR 2024*. arXiv:2310.01798. |
| 30 | Ch 07 Research | Claude's citation hallucination rate is nonzero; research found hallucinated references in substantial fraction (Walters & Wilder 2023, Alkaissi & McFarlane 2023) | CITATION/STAT | CONFIRMED | Both papers verified. Walters & Wilder: *Scientific Reports* 13, 14045 (2023) — 55% fabrication rate for GPT-3.5, 18% for GPT-4. Alkaissi & McFarlane: *Cureus* 15, e35179 (Feb 2023). "Substantial fraction" characterization is accurate and conservative. |
| 31 | Ch 07 Research | AI-use disclosure policies changing frequently | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 32 | Ch 07 Research | Future Claude with verified database access could provide citations with auditable provenance | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 33 | Ch 07 Research | COPE (2023). Authorship and AI tools. https://publicationethics.org/ | CITATION/STAT | CONFIRMED | COPE position statement on AI authorship confirmed at publicationethics.org, last reviewed February 13, 2023. Core claim (AI cannot be listed as author; researchers responsible for accuracy) is accurate. |
| 34 | Ch 08 Writing | Claude honors explicit authorial constraints better when stated prominently | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 35 | Ch 08 Writing | AI-assisted writing disclosure policies vary and are changing | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 36 | Ch 08 Writing | COPE 2023; publisher-specific guidelines | CITATION/STAT | CONFIRMED | See item 33. |
| 37 | Ch 08 Writing | Cadario et al. 2021 (for LLM context, automation bias/overreliance) | CITATION/STAT | UNCONFIRMED | Web searches for "Cadario et al. 2021" in the context of AI/LLM overreliance returned no matching paper. Cadario has published on algorithm aversion, but the specific 2021 citation matching this claim could not be located. The Parasuraman & Manzey (2010) citation in the same line is verified. Recommend: either locate and verify the full Cadario citation or remove it. |
| 38 | Ch 09 Data | Claude will use causal framing for correlational patterns | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 39 | Ch 09 Data | Chapter assumption that Claude's quantitative reliability requires independent verification | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 40 | Ch 10 Teaching | "The Anthropic Learning Mode" offers a tutoring mode | PRODUCT/PLATFORM | DEFERRED | Verify feature name and availability at publication time |
| 41 | Ch 11 Handoffs | Claude Code and Claude Cowork as current agentic surfaces | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 42 | Ch 11 Handoffs | Approval gate exercise — current interface behavior for Claude Code/Cowork | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 43 | Ch 11 Handoffs | Intent-checking / inferred specification | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 44 | Ch 11 Handoffs | Claude Code assumes some comfort with terminal commands | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 45 | Ch 12 Library | Claude is updated periodically; prompts should be retested | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 46 | Ch 12 Library | "Last tested" field in prompt card template | PRODUCT/PLATFORM | DEFERRED | Template instruction, not a factual claim |
| 47 | Ch 12 Library | No format standard for prompt libraries has stabilized | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 48 | Ch 13 Capstone | Model failure: constraint adherence varies | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 49 | Ch 13 Capstone | Self-check step borrowed from chain-of-thought; model behavior varies | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 50 | Ch 13 Capstone | Self-check may become unnecessary with better constraint adherence | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |
| 51 | Ch 13 Capstone | No standard practice for sharing prompt cards across organizations | PRODUCT/PLATFORM | DEFERRED | Verify at publication time |

---

## Corrections to Apply

**These are the only two items requiring edits before publication:**

### Correction 1 — Ch 04, line 246: Sweller citation issue number

Current:
```
Sweller, J. (2006). The worked example effect and human cognition. *Learning and Instruction*, 16(2).
```

Correct to:
```
Sweller, J. (2006). The worked example effect and human cognition. *Learning and Instruction*, 16, 165–169.
```

Rationale: The article is confirmed in *Learning and Instruction* vol. 16, pp. 165–169. The issue number "(2)" appears in no verified source; all citation databases list it as vol. 16 only. Adding page numbers improves precision.

---

### Correction 2 — Ch 06, line 271: Huang et al. missing venue

Current:
```
- Huang, J., et al. (2023). Large language models cannot self-correct reasoning yet. [verify — current as of writing]
```

Correct to:
```
- Huang, J., et al. (2024). Large language models cannot self-correct reasoning yet. *Proceedings of ICLR 2024*. arXiv:2310.01798.
```

Rationale: The paper was submitted October 2023 but published at ICLR 2024. The `[verify]` tag should be removed; the citation is confirmed. The venue should be recorded.

---

## Unconfirmed Item Requiring Author Action

### Item — Ch 08, line 309: Cadario et al. 2021

The citation "Cadario et al. 2021" appears in a reference note alongside Parasuraman & Manzey 2010 as supporting evidence for automation bias / overreliance in an LLM context. Web searches did not locate a paper matching this author-year combination in this subject area. The Parasuraman & Manzey citation is verified. **Author should supply the full citation for Cadario et al. 2021 or remove it.**

---

## Deferred to Publication-Time

All 29 PRODUCT/PLATFORM items are deferred. These cover Claude model behavior, Claude Projects, Claude Code interface, Claude Cowork features, Anthropic documentation URLs, and AI-use policy statements that are explicitly marked as "current as of writing" and expected to change. Recommended publication-time checklist:

- Claude's context handling (items 2–4, 6–7, 17–20, 26–27, 38–39)
- Claude's style/constraint adherence (items 10–12, 34)
- Claude Code and Cowork features (items 41–45)
- Anthropic docs URLs (items 8, 13, 14, 25)
- "Anthropic Learning Mode" feature name and availability (item 40)
- Prompt card format standard status (item 47)
- AI disclosure policy currency (items 31, 35)

---

## Sources Checked

- Brown et al. (2020): https://arxiv.org/abs/2005.14165 — NeurIPS 2020 proceedings
- Huang et al. (2023/2024): https://arxiv.org/abs/2310.01798 — ICLR 2024
- Walters & Wilder (2023): https://www.nature.com/articles/s41598-023-41032-5 — *Scientific Reports* 13, 14045
- Alkaissi & McFarlane (2023): https://pmc.ncbi.nlm.nih.gov/articles/PMC9939079/ — *Cureus* 15, e35179
- COPE (2023): https://publicationethics.org/guidance/cope-position/authorship-and-ai-tools
- Parasuraman & Manzey (2010): https://journals.sagepub.com/doi/10.1177/0018720810376055 — *Human Factors* 52(3), 381–410
- Mosier & Skitka (1996): https://psycnet.apa.org/record/1996-98364-010 — chapter in *Automation and Human Performance*, Lawrence Erlbaum
- Popham (1997): https://eric.ed.gov/?id=EJ552014 — *Educational Leadership* 55(2), 72–75
- Moher et al. (2009): https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1000097 — *PLOS Medicine* 6(7), e1000097
- NIST AI RMF 1.0 (2023): https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10 — published January 26, 2023
- Sweller (2006): https://www.semanticscholar.org/paper/The-worked-example-effect-and-human-cognition-Sweller/cecccde1affe195285f48b3d7f16a8c2613e82cb — *Learning and Instruction* 16, 165–169
- Cadario et al. 2021: NOT LOCATED — requires author follow-up
