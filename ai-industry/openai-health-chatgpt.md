---
type: analysis
title: Health in ChatGPT — OpenAI connects medical records and Apple Health
description: OpenAI launches Health in ChatGPT for US users — opt-in connection of medical records and Apple Health so conversations can draw on labs, medications and activity data; 300M+ weekly health queries, physician-built evals, and explicit no-training/no-ads commitments.
bundle: political-economy
topic: ai-industry
tags:
- ai-industry
- digital-privacy
- us-politics
resource: https://openai.com/index/health-in-chatgpt/
sources:
- id: 2026-08-04-launching-health-in-chatgpt
  resource: Resources/web-clippings/2026-08-04-Launching Health in ChatGPT.md
generated:
  by: claude-code/atlas-consolidate
  at: '2026-08-05T09:00:00Z'
status: stable
related:
- political-economy/ai-industry/openai-presence-enterprise-agents.md
- political-economy/china-domestic-economy/china-medical-tourism.md
---

# Health in ChatGPT — OpenAI connects medical records and Apple Health

**Source:** [Launching Health in ChatGPT](https://openai.com/index/health-in-chatgpt/)
**Author:** OpenAI (published 30 July 2026)

---

## Summary

OpenAI is rolling out Health in ChatGPT to US users 18+, letting them securely connect Apple Health and supported medical records so ChatGPT can compare new lab results with prior tests, summarise changes since a last appointment, and personalise everyday conversations (a dietary restriction when choosing a restaurant, an injury when planning activities). More than 300 million people ask ChatGPT health-related questions weekly, but the context is scattered across portals, records, apps and wearables (source: 2026-08-04-Launching Health in ChatGPT.md).

## Design shift: from destination to context layer

An earlier limited release required visiting a dedicated health space; testing showed more than 70% of health-related conversations happened outside it, so Health now works as connected context across all conversations, with the sidebar Health section as the management home base for accounts, trends, synced records and past health conversations (source: 2026-08-04-Launching Health in ChatGPT.md).

## Models and physician evaluation

- GPT-5.5 Instant brought "frontier health intelligence" to free users — gains in recognising when urgent care may be needed, asking for context, explaining uncertainty; GPT-5.6 Sol (paid) is OpenAI's strongest health model, outperforming GPT-5.5 on HealthBench Professional across the board (source: 2026-08-04-Launching Health in ChatGPT.md).
- Hundreds of physicians worldwide build scenario rubrics assessing accuracy, safety, communication, context awareness, completeness and escalation; on the published criteria chart GPT-5.6 Sol scores 91.0% (accuracy), 86.7% (communicates clearly), 88.0% (completeness), 93.8% (follows instructions) and 83.0% (health-decision helpfulness) — in each case above physician-written responses (76.2/61.0/53.2/74.4/50.8) — while OpenAI stresses ChatGPT still makes mistakes and does not replace professional care (source: 2026-08-04-Launching Health in ChatGPT.md).

## Privacy architecture

- Connected medical records and Apple Health data — and conversations using them — are not used to train foundation models or target ads, regardless of the user's model-training settings; the data gets additional encryption on top of standard conversation encryption (source: 2026-08-04-Launching Health in ChatGPT.md).
- By default ChatGPT asks permission before using connected health information in a response (always-allow is optional); disconnecting a source deletes its synced data from OpenAI systems within 30 days, though data already in conversation history persists until those conversations are deleted (source: 2026-08-04-Launching Health in ChatGPT.md).

## Key Takeaways

- OpenAI is positioning ChatGPT as the interpretive layer over the fragmented US health-data landscape — the assistant that sees the whole record when no portal does.
- Beating physician-written responses on physician-graded rubrics is the core legitimacy claim; the escalation/safety criteria are where liability and regulation will focus.
- The no-training/no-ads carve-out concedes that health data demands a separate trust regime — a template likely to be demanded for other sensitive verticals.
- Strategically this is a consumer-data moat: connected records raise switching costs in exactly the domain (health) where user trust is hardest to win and most valuable.

## Related

- [[openai-presence-enterprise-agents]] · [OpenAI Presence](../ai-industry/openai-presence-enterprise-agents.md) — the enterprise-side counterpart in OpenAI's product expansion the same week
- [[china-medical-tourism]] · [China medical tourism](../china-domestic-economy/china-medical-tourism.md) — the state-led mirror image: health data harvested as strategic asset for AI medicine
