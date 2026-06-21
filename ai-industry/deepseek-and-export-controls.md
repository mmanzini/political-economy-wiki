---
type: analysis
title: DeepSeek and Export Controls
description: Dario Amodei argues that DeepSeek-V3 is an expected point on the AI cost reduction curve (not a paradigm shift), but that its geopolitical significance — a Chinese lab reaching near-frontier performance first — makes chip export controls more important, not less.
bucket: political-economy
topic: ai-industry
tags: []
source: https://darioamodei.com
resource: https://darioamodei.com
timestamp: 2026-05-09T07:13:14Z
status: active
related:
  - political-economy/ai-geopolitics-and-risks/ai-transformative-potential.md
  - political-economy/ai-geopolitics-and-risks/ai-risks-and-safety.md
  - political-economy/ai-industry/ai-developments-april-2026.md
---

# DeepSeek and Export Controls

**Source:** [Dario Amodei, "On DeepSeek and Export Controls"](https://darioamodei.com)
**Author:** Dario Amodei

---

*Source: Dario Amodei, "On DeepSeek and Export Controls" (darioamodei.com, January 2025)*

## Summary

Dario Amodei argues that DeepSeek-V3 is an expected point on the AI cost reduction curve (not a paradigm shift), but that its geopolitical significance — a Chinese lab reaching near-frontier performance first — makes chip export controls more important, not less. The essay lays out why the 2026–2027 period is critical and why only well-enforced export controls can prevent a bipolar AI world.

## Three Dynamics of AI Development

- **Scaling laws**: more compute → smoothly better results across cognitive tasks; each 10x increase maps to a major capability jump (source: darioamodei.com)
- **Shifting the curve**: algorithmic innovations and new hardware act as "compute multipliers" (CM) — estimated ~4x/year overall. Companies reinvest savings into training smarter models, not cheaper ones. AI cost per fixed quality drops, but frontier spend keeps rising.
- **Shifting the paradigm**: reinforcement learning (RL) for chain-of-thought reasoning is a new second stage of training (post-2024). Still early on the scaling curve → large gains from small spend. This is why multiple companies can temporarily produce competitive reasoning models.

## DeepSeek's Models

### DeepSeek-V3 (pretrained model)
- The real innovation — close to US frontier model performance on some tasks, at lower training cost
- Key innovations: KV-cache management and pushing mixture-of-experts further
- **Not "$6M vs. billions"**: Anthropic's Claude 3.5 Sonnet cost a few $10M to train (9–12 months earlier), and Sonnet still beats DeepSeek on coding and many internal evals
- Fair characterisation: "produced a model close to US models 7–10 months older, for less cost — but not the ratios people suggest"
- On-trend with the historical ~4x/year cost reduction curve, not a paradigm-breaking leap
- **What's different**: first time a Chinese company demonstrated expected cost reductions before US labs. Geopolitically significant.

### DeepSeek-R1 (reasoning model)
- Less innovative than V3; adds RL second stage (replicating OpenAI's o1)
- Cheap to produce given V3 as a base
- First model to **show chain-of-thought reasoning to users** (UI choice, not model innovation)
- Triggered ~17% Nvidia stock drop (which Amodei calls "baffling" — the release is if anything good for Nvidia)

### DeepSeek's Actual Resources
- Reported: **50,000 Hopper-generation chips** (mix of H100, H800, H20) — ~$1B
- Within 2–3x of major US AI companies' clusters
- Total company spend **not vastly different** from US labs

## Export Controls Argument

- Making AI smarter than almost all humans at almost all things will require **millions of chips and tens of billions of dollars** — most likely **2026–2027**
- Two possible worlds:
  - **Bipolar**: both US and China have millions of chips → both have "countries of geniuses in a datacenter." China could potentially take a commanding lead due to greater military focus and industrial base.
  - **Unipolar**: only US and allies have the chips → temporary lead that could become **durable** because AI systems help make even smarter AI systems (recursive advantage)
- **Well-enforced export controls** are the single most important determinant of which world we get
- DeepSeek doesn't show export controls failed — they had moderate chips, and the controls weren't designed to block $1B of activity. Blocking $10B–$100B is realistic.
- DeepSeek's chip mix confirms controls are adapting: H100s likely smuggled, H800s shipped before ban, H20s still legal (but should be banned) (source: darioamodei.com)
- China's own chips (Huawei Ascend) **substantially lag** Nvidia; no significant clusters outside China (source: darioamodei.com)
- $1B can be hidden; $100B cannot. A million chips may be physically difficult to smuggle. (source: darioamodei.com)

## Key Takeaways

- DeepSeek-V3 is an expected point on the cost reduction curve, not a paradigm shift — but the fact that a Chinese company got there first is geopolitically significant
- The RL reasoning paradigm (R1) is still early on its scaling curve; current parity is temporary and will disappear as companies scale up
- Export controls are **more** important after DeepSeek, not less — more powerful AI per chip means the chip bottleneck is even more critical
- The goal is not to target DeepSeek specifically, but to prevent any authoritarian government from matching US AI capability during the critical 2026–2027 period

## Related

- [[ai-transformative-potential]] — Amodei's vision of what "countries of geniuses in a datacenter" could achieve
- [[ai-risks-and-safety]] — the risks of powerful AI, including misuse by authoritarian states
- [[ai-developments-april-2026]] — current AI industry developments

## Tags

#political-economy #ai-industry #deepseek #export-controls #china #chips
