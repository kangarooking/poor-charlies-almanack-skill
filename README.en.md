# Poor Charlie's Almanack Skill

A ready-to-use AI skill pack — 12 composable reasoning modules distilled from Charlie Munger's core thinking methods.

This is not a book summary page. The book is the source; these skills are the product.

## What Problems Do These Skills Solve

- Making important decisions without relying solely on intuition
- Identifying cognitive biases, incentive distortions, and blind spots
- Turning concepts like "inversion thinking," "circle of competence," and "mental models" into callable tools
- Building a reusable framework for investment and business analysis
- Introducing structured checks into team decisions instead of gut-feeling calls

## What Was Distilled

12 triple-verified skills extracted from *Poor Charlie's Almanack*, covering four dimensions:

- **Core Thinking**: `inversion-thinking`, `latticework-mental-models`, `darwinian-objectivity`, `circle-of-competence`
- **Cognitive Bias Defense**: `dual-track-analysis`, `misjudgment-psychology-checklist`, `lollapalooza-effect`, `incentive-analysis`, `deprival-superreaction`
- **Investing & Business**: `value-assessment`, `scale-advantage-analysis`
- **Execution Framework**: `checklist-decision`

The extraction process started with 49 candidate units and achieved a 24.5% pass rate — only 1 in 4 candidates became a skill.

## Effect Examples

### Example 1: Self-Doubt in Investment Decisions

**User Question**

"I'm considering investing in a SaaS company. It's growing fast, but I feel like I might just be swayed by the founder's pitch. How do I check?"

**Skill Judgment**

- Trigger `circle-of-competence` — is this company within your genuine understanding?
- Trigger `darwinian-objectivity` — force-search for disconfirming evidence
- Call `incentive-analysis` — check whether founder, investor, and sales incentives are aligned
- Finish with `checklist-decision` — consolidate judgment into a reviewable checklist

**Response Example**

> Don't first decide if it's a good company — first decide if it's a company you genuinely understand. You need to answer four things: why it can keep growing, why customers won't easily churn, what's most likely to break its growth in the next 2-3 years, and whether it would still function without the founder. If you can't clearly answer two of these, it's probably outside your circle of competence. Then invert: under what conditions would this company fail? The three most common answers are customer acquisition costs spiraling, high product substitutability, and misaligned team incentives. Compile these into a checklist before deciding to continue research — don't jump to a verdict.

### Example 2: The Scale Advantage Trap

**User Question**

"An industry leader keeps getting bigger — does that automatically mean more advantage?"

**Skill Judgment**

- Trigger `scale-advantage-analysis`
- If extreme outcomes are involved, supplement with `lollapalooza-effect`
- If it leads to an investment decision, follow up with `value-assessment`

**Response Example**

> Scale does not automatically equal advantage. First, look at what scale brings: lower procurement costs, stronger brand recognition, network effects, or expanded information advantages. Then look at what scale starts to cost: organizational bloat, slower decisions, distorted incentives, increased internal politics. What matters is not "how big" but whether scale advantages are still compounding or already being eaten by bureaucratic costs. If both forces are present simultaneously, you can't default to "stronger" just because it's the market leader.

## How These Skills Were Generated

These skills were produced using the **cangjie-skill** RIA-TV++ pipeline, a six-stage process:

1. **Whole-Book Comprehension (Adler Analysis)** — Structural, interpretive, critical, and applicability analysis of the entire book, producing `BOOK_OVERVIEW.md`
2. **Parallel Extraction** — Five specialized extractors (frameworks, principles, cases, counter-examples, glossary) run simultaneously to pull candidate units from the source text
3. **Triple Verification** — Each candidate must pass three checks: at least 2 independent supporting passages in the book (cross-domain), ability to answer a novel question not explicitly addressed (predictive power), and non-commonsense uniqueness. Pass rate is typically 25-50%
4. **RIA++ Construction** — Verified content is structured into six dimensions: R (original quote) / I (own-words reconstruction) / A1 (book cases) / A2 (future trigger scenarios) / E (executable steps) / B (boundaries & blind spots)
5. **Zettelkasten Linking** — Dependency, contrast, and composition relationships between skills are identified, producing `INDEX.md` with a reference graph
6. **Pressure Testing** — Test prompts including bait questions are designed for each skill; failures go back to Stage 4 for full reconstruction

Every `SKILL.md` is a real output of this process. `candidates/` and `rejected/` directories are preserved as a complete audit trail.

## Generated by Cangjie Skill

This repository was generated by [cangjie-skill](https://github.com/kangarooking/cangjie-skill) — an open-source toolchain that distills books into executable AI skills.

Built on the RIA-TV++ methodology, cangjie-skill extracts methodologies, frameworks, and principles from books into atomic skills that AI agents can invoke in real-world scenarios.

## Repository Structure

```text
poor-charlies-almanack-skill/
├── README.md              ← You are here
├── README.en.md           ← English version
├── README.ja.md           ← Japanese version
├── LICENSE                ← MIT
├── BOOK_OVERVIEW.md       ← Stage 0 output: full-book Adler analysis
├── INDEX.md               ← Stage 3 output: skill overview + reference graph
├── candidates/            ← Stage 1 output: 49 raw candidate units
├── rejected/              ← Stage 1.5 output: 37 rejected units + reasons
├── verified.md            ← 12 units that passed triple verification
└── */SKILL.md             ← 12 skills, each with test-prompts.json
```

## How to Use

1. Browse `INDEX.md` for the full skill map and dependency relationships
2. Find the `*/SKILL.md` relevant to your current problem and use its trigger conditions and execution steps
3. Integrate skills into your agent framework, or use prompts as standalone tools
4. Validate with `test-prompts.json` — skills should trigger in the right scenarios and stay silent in the wrong ones

## Source

- Book: *Poor Charlie's Almanack*
- Core figure: Charlie Munger
- Compiler: Peter D. Kaufman

## More Skills

- [Buffett Letters Skill](https://github.com/kangarooking/buffett-letters-skill) — 20 investment reasoning skills from Buffett's 60+ years of shareholder letters
- [No Rules Rules Skill](https://github.com/kangarooking/no-rules-rules-skill) — 10 organizational design skills from Netflix's culture of freedom and responsibility
- [Cognitive Dividend Skill](https://github.com/kangarooking/cognitive-dividend-skill) — 15 cognitive tool skills for thinking upgrades from Cognitive Dividend
- [Duan Yongping Skill](https://github.com/kangarooking/duan-yongping-skill) — 15 business and investment skills from Duan Yongping's Q&A collection

## About the Author

**kangarooking** — AI blogger, indie developer. Creator of AI Top WeChat Official Account「袋鼠帝 AI 客栈」

Volcengine Navigation KOL, Baidu Qianfan Developer Ambassador, GLM Evangelist, Trae Kunming's First Fellow

| Platform | Link |
|----------|------|
| 𝕏 Twitter | https://x.com/aikangarooking |
| Xiaohongshu | https://xhslink.com/m/5YejKvIDBbL |
| Douyin | https://v.douyin.com/hYpsjphuuKc |
| WeChat Official Account | 袋鼠帝 AI 客栈 |
| WeChat Video Channel | AI 袋鼠帝 |

WeChat Official Account「袋鼠帝 AI 客栈」QR code:

![](https://raw.githubusercontent.com/kangarooking/cangjie-skill/main/assets/kangarooking-gzh.jpg)

## License

MIT. See [LICENSE](./LICENSE).
