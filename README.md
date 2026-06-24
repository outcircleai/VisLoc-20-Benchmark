# The VisLoc-20 Benchmark 🌍
**A deterministic evaluation suite for AI Video Localization, UI Physics, and Transcreation.**

Standard AI translation evaluates text on "meaning" in a vacuum. But in short-form video, translation is bound by strict **UI Physics**. Standard tools use "greedy pixel filling" and literal translation. When translating from English to German (which expands character count by 30%), these architectures fail catastrophically: they chop words in half, stride over UI buttons, or drop active marketing hooks.

We built the **VisLoc-20 (Visual Localization 20-Point Standard)** to test the limits of cross-lingual AI architectures against the physical constraints of short-form video.

## 🧪 The Axes of Failure
1. **Layout & Physics:** Typography crashes and spaceless script boundaries.
2. **Semantic Context:** Slang, B2B jargon, and legal restrictions.
3. **UI Safe-Zones:** TikTok/LinkedIn grid avoidance.
4. **Acoustic ASR Traps:** Stutters, aggressive speaker overlap, and noise.
5. **The Pareto Squeeze:** Math vs. Meaning limits.
6. **Origin-Agnostic Processing:** Mandarin/Spanish expansion dynamics.

## 🚀 How to Use
1. Clone this repository to access the 20 raw `.mp4` files in `/source_videos`.
2. Run these videos through your AI video translation tool.
3. Evaluate the localized output against the `SCORING_RUBRIC.md` and the `visloc_ground_truth.json` answer key.
*Note: Any output that requires a human to manually drag a timeline slider or hit 'Enter' to fix a line break has failed the automation test.*
