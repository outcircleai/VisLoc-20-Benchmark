# The VisLoc-20 Benchmark 🌍

A deterministic evaluation suite for AI Video Localization, UI Physics, and Transcreation.

The VisLoc-20 benchmark was built to test the [OutCaps Deterministic Layout Engine](https://outcaps.com). You can read the full engineering report and visual teardowns here: [outcaps.com/visloc-benchmark](https://outcaps.com/visloc-benchmark)

Standard AI translation evaluates text on "meaning" in a vacuum. But in short-form video, translation is bound by strict **UI Physics**. Standard tools use "greedy pixel filling" and literal translation. When translating from English to German (which expands character count by ~30%), these architectures fail catastrophically: they chop words in half, stride over UI buttons, or drop active marketing hooks.

We built the **VisLoc-20** (Visual Localization 20-Point Standard) to test the limits of cross-lingual AI architectures against the physical constraints of short-form video.

## 🧪 The 6 Edge-Case Categories

Each of the 20 test videos targets one or more of these failure categories:

1. **Layout & Physics** — Typography crashes, spaceless script boundaries, and CJK line-break failures.
2. **Semantic Context** — Slang, B2B jargon, idioms, and legal restrictions that break literal translation.
3. **UI Safe-Zones** — TikTok/Reels/LinkedIn grid avoidance and overlay collision.
4. **Acoustic ASR Traps** — Stutters, aggressive speaker overlap, and background noise.
5. **The Pareto Squeeze** — Math vs. Meaning limits: when text expansion forces a tradeoff between readability and completeness.
6. **Origin-Agnostic Processing** — Non-English source videos (Mandarin, Spanish) and their expansion dynamics.

## 📊 The 3 Scoring Axes

Each video is scored on **3 axes** (100 points total):

| Axis | Weight | What It Measures |
| :--- | :---: | :--- |
| **UI Physics & Pacing** | 40/100 | Word splits, CPS (Characters/Second) violations, flicker, safe zone compliance |
| **Semantic Yield** | 40/100 | Meaning preservation, cultural transcreation, tone/register accuracy |
| **Aesthetic & Layout** | 20/100 | Line-wrap quality, orphaned words, visual balance, text density |

> **Note**: Scores are strictly capped at 100/100. There are no bonus points. Deductions are sourced from the internal translation quality rubric with specific, documented evidence per violation.

## 🚀 How to Use

1. Clone this repository to access the 20 raw `.mp4` files in `/source_videos`.
2. Run these videos through your AI video translation tool.
3. Evaluate the localized output against the `SCORING_RUBRIC.md` and the `visloc_ground_truth.json` answer key.

> **Note**: Any output that requires a human to manually drag a timeline slider or hit 'Enter' to fix a line break has failed the automation test.
