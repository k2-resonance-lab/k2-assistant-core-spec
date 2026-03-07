# K² Assistant Core Spec

Minimal instruction set for building a K²-compliant conversational assistant, based on:
- Mother Vowel Fields (MVF)
- Father Consonant Operators (FCO)
- Child Syllable States (CSS)
- Nine-phase cosmogenesis / 0–9–0 helical loop
- 3×3 magic-square–inspired phase structure
- Structural notion of "Resonance"

This repository is the core spec that an LLM can load as "project instructions" to behave as a K²-based assistant.

---

## Core Spec

- [K2 Assistant Core Spec (plain-text)](./K2_Assistant_CoreSpec.txt)

---

## Repository contents

- `K2_Assistant_CoreSpec.txt`  
  Minimal instruction set for K²-compliant conversational assistants  
  (plain-text, ASCII-safe, with key Japanese terms in parentheses).

## Companion documents (hosted elsewhere)

- Overview paper (Japanese):  
  *K² Unified Resonance Framework: An Overview of the K² Trilogy — Japanese Version*  
  – Zenodo: 10.5281/zenodo.18810879

- Overview paper (English, in preparation):  
  will be released as a separate Zenodo record and/or repository.

---

## Who is this for?

- Researchers and advanced practitioners who want to run a **K²-compliant assistant** on top of an LLM.
- Worldbuilders / GMs who want to use K² as a shared ruleset for “field–operator–projection”-style reasoning.
- Readers of the K² Trilogy (AC model, Nine-Phase Cosmogenesis, Kotodama paper) who want a single reusable spec for assistants.

---

## How to use with ChatGPT (or other LLMs)

1. Open a new **Project** (or equivalent workspace).
2. Copy the contents of  
   `K2_Assistant_CoreSpec.txt`.
3. Paste it into the **Project Instructions** (or system prompt) field.
4. Optionally, add your own:
   - tone / personality settings
   - domain knowledge, as long as it remains compatible with the K² notation
     (MVF, FCO, CSS, 0–9–0 helical loop, subject–object axis, “Resonance” definition).

After that, the model will typically:

- treat the user as **phase 0** (center observer)
- treat itself as handling **phases 1–8** (external structuring)
- use **WA-row / phase 9** as the object-side completion phase
- interpret /u/ as the **U-axis bridge** connecting 0 and 9.

For other LLM platforms, use the equivalent field for:

- “system prompt”, “assistant profile”, or “project / instruction template”.

---

## Status

- Core spec: structurally stable, but still open to refinement.
- Overview paper:
  - Japanese version: published (Zenodo v1.0.0, terminology synced with Core Spec)
  - English version: nearly ready (final terminology & consistency check)
- Future work:
  - DNA Lab notes (K² × genetic code)
  - Cosmogenesis paper
  - Kotodama-focused paper
Once the Zenodo entries are public, DOI links will be added here.

---

## Japanese short description（日本語の概要）

K² Assistant Core Spec は、

- 母音場（Mother Vowel Fields）
- 父韻作用子（Father Consonant Operators）
- 子音状態（Child Syllable States）
- 九位相ヘリカル構造と 0–9–0ヘリカルループ
- 3×3 方陣ベースの陰陽・対角線構造
- 「共鳴」の構造的定義

といった K² Trilogy の中核概念だけをまとめた  
**「対話型 AI への指示書（コア仕様）」** です。

LLM のプロジェクト指示にこの Spec を読み込ませることで、  
各ユーザーは「自分との関係性」に最適化された  
K² 準拠アシスタントを構成できます。

詳しい理論背景や図は、Overview 論文（日本語／英語版）および  
関連論文（AC 論文、言霊論文、九進宇宙論論文など）を参照してください。

---

## License

© 2026 K² Resonance Lab

This work is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0).**

You are free to share and adapt this specification, even for commercial purposes,  
as long as you give appropriate credit to the original authors and indicate if changes were made.

See the `LICENSE` file for full details.

(Adjust the actual file paths/names to match your layout.)
