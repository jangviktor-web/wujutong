<div align="center">
  
<img width="120" alt="1000015201" src="https://github.com/user-attachments/assets/89af8070-a9f7-4c74-9f27-11e9426d1343" />


# 🩺 Master of the Warm Disease School · Wu Jutong Skill

> **The great synthesizer of the Warm Disease (Wenbing) School · A Sanjiao (Triple Burner) Pattern-Based Diagnostic Operating System**
>
> Distilled from *Systematized Identification of Warm Diseases*, *Wu Jutong's Medical Cases*, *Medical Essays on Healing*, and *Exegesis of the Warm and Heat Classics* into an AI-callable, independently reasoning, and clinically challengeable role skill.



[![Version](https://img.shields.io/badge/version-V3.1-2ea44f?style=flat-square)](#-version-history)
[![Cases](https://img.shields.io/badge/Medical%20Cases-359%20cases-blueviolet?style=flat-square)](#-medical-case-library)
[![Categories](https://img.shields.io/badge/Patterns-45%20categories-orange?style=flat-square)](#-medical-case-library)
[![References](https://img.shields.io/badge/References-13%20papers-9cf?style=flat-square)](#-directory-structure)
[![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)](#-license)
[![GitHub stars](https://img.shields.io/github/stars/jangviktor-web/wujutong?style=flat-square)](https://github.com/jangviktor-web/wujutong)

</div>

---

## ✨ One‑Sentence Summary

> **"Differentiates the Triple Burner, tracks the Wei–Qi–Ying–Blood transmission, excels in using pungent-cooling and clear–heat formulas, and sharply criticises the contemporary abuse of warm-tonifying methods."**
>
> When you ask an AI a question about a warm disease, it will **no longer mechanically apply the Six-Meridian template** from the *Shanghan Lun*. Instead, it steps into Wu Jutong's shoes and first asks: "In which Burner is the disease (Lung/Spleen-Stomach/Liver-Kidney)?", "At which level of Wei–Qi–Ying–Blood has it progressed?", and "What is the state of the body fluids (Jin-Ye)?" Only then does it decide whether to use **Yin-Qiao San** (pungent-cooling moderate formula), **Qing-Ying Tang** (cool the Ying and vent heat), or the **Fu-Mai approach** (nourish Yin).

---
## Quick Install

<details open>
<summary><b> ClawHub (Recommended)</b></summary>

```bash
openclaw skills install @jangviktor-web/wujutong
```

</details>

<details>
<summary><b>OpenClaw / OpenClawMP / Manual</b></summary>

```bash
# OpenClaw
openclaw skills install @jangviktor-web/wujutong


# Manual
git clone https://github.com/jangviktor-web/wujutong.git
cp -r wujutong/ ~/.claude/skills/wujutong/
```

</details>

<details>
<summary><b>Mobile (Tencent IMA APP)</b></summary>

Download the Tencent IMA APP, go to Copilot Skills, search for "Wu Jutong" and install.

</details>

---

📑 Table of Contents

· 🎯 Why This Skill?
· 🚀 Core Capabilities (6 Pillars)
· 🆚 Classic-Formula vs Warm-Disease Schools (10-Dimensional Comparison)
· 📂 Directory Structure
· 🩺 Sanjiao Differentiation: The Core Framework
· 💊 Quick Formula Reference (22 Core Formulas by Burner)
· 📚 Medical Case Library (45 Patterns · 359 Cases)
· 🛡️ Clinical Safety Layer (5 Lethal Pathways + 31 Immutable Rules)
· 🎭 Role-Play Examples
· 📊 Version History
· 🙏 Acknowledgements & Sources
· ⚠️ Disclaimer
· 📄 License

---

🎯 Why This Skill?

Common pitfalls when using AI in Chinese medicine:

Issue Consequence How This Skill Resolves It
Blindly applying the Six-Meridian framework Warm diseases are mis‑treated with Ma-Huang/Gui-Zhi → "adds fuel to the fire" An independent Triple-Burner diagnostic framework
Not distinguishing warm‑heat / damp‑heat / dryness pathogens Misplaced therapeutic approach 9 core diagnostic formulas + Wei‑Qi‑Ying‑Blood progression logic
Abusing warm-tonifying or cold-cooling herbs Worsens the patient's condition 31 therapeutic rules + Four Prohibitions of Bai-Hu Tang + Three Prohibitions for Damp‑Warmth
No grounding in historical cases Vague, generic responses 359 cases + 45 patterns + dual index (pathogenesis / formula / symptom)
Inconsistent role‑play Unreliable answers 7‑segment role‑play rules (source → pattern differentiation → canonical citations → formula → warnings → reflection → boundaries)

---

🚀 Core Capabilities (6 Pillars)

1️⃣ Sanjiao (Triple Burner) Differentiation Framework

· Upper Burner (Lung/Pericardium): 3‑stage pungent‑cooling → Yin-Qiao San, Sang-Ju Yin, Bai-Hu Tang
· Middle Burner (Spleen/Stomach/Large Intestine): Clear heat and preserve fluids → Bai-Hu Tang, Cheng-Qi formulas, Zeng-Ye Tang
· Lower Burner (Liver/Kidney): Nourish Yin and subdue Yang → Fu-Mai Tang, San-Jia Fu-Mai, Qing-Hao Bie-Jia Tang
· See references/01-core-philosophy.md

2️⃣ Wei‑Qi‑Ying‑Blood Progression Assessment

· Wei Level (Exterior): slight fever with aversion to cold → Yin-Qiao San
· Qi Level (Interior): high fever, intense thirst, profuse sweating, surging pulse → Bai-Hu Tang
· Ying Level (Heat entering Pericardium): crimson tongue, delirium → Qing-Ying Tang + An-Gong Niu-Huang Wan
· Xue Level (Heat entering Blood): macules, bleeding → Xi-Jiao Di-Huang Tang
· See references/29-diagnostic-formulas.md (10 core formulas)

3️⃣ 22 Core Formulas System

Organised by Triple Burner, covering all stages of warm diseases. See references/24-formula-pattern-system.md.

4️⃣ 359 Medical Cases (The Biggest Feature)

· 45 disease pattern categories (complete coverage of Volumes 1–5 of the original text)
· Each case as a separate .md file with: patient info, age, consultation date, formula, modifications
· Dual quick‑lookup indices:
  · _index.md (organised by volume + disease pattern)
  · _quick-lookup.md (4‑dimension cross‑reference: pathogenesis / Sanjiao / formula / symptom)

5️⃣ Clinical Safety Layer

· Five lethal pathways in warm diseases (warning signs of depletion of the source of transformation in Lung, Heart, Liver, Spleen, Kidney)
· Four Prohibitions of Bai-Hu Tang (pulse floating/sinewy/thready, sunken pulse, no thirst, no sweating)
· Three Prohibitions for Damp‑Warmth (no sweating, no purging, no moistening)
· 26 emergency formulas for iatrogenic mistreatment
· See references/09-clinical-safety.md

6️⃣ Cross‑School Dialogue Capability

· Paired with nihaixia (Ni Haixia · Classic-Formula School): same case, four‑round debate
· Both consensus and divergence are clearly articulated (both revere Zhang Zhongjing, both emphasise pattern differentiation over fixed formulas)
· See README §Cross‑School Comparison

---

🆚 Classic-Formula vs Warm-Disease Schools (10‑Dimensional Comparison)

Same case: summer high fever 39.2°C, slight aversion to cold + sore throat + thirst + floating/rapid pulse

Dimension Ni Haixia (Classic‑Formula) Wu Jutong (Warm‑Disease)
Diagnostic Framework Six-Meridian Differentiation Sanjiao + Wei‑Qi‑Ying‑Blood
Etiology Wind‑Cold / Wind‑Heat Warm Pathogen (with Damp / Wind / Summer‑Heat)
Path of Invasion Taiyang → Yangming → Shaoyang → Taiyin → Shaoyin → Jueyin Upper Burner → Middle Burner → Lower Burner (Wei→Qi→Ying→Xue)
Core Therapeutic Principle Expel the pathogen (sweat/emesis/purging/harmonising/warming/clearing/tonifying/dispersing) Preserve the body fluids + eliminate pathogenic heat
Slight Aversion to Cold Exterior pattern not yet resolved (still Ma-Huang/Gui-Zhi suitable) Warm pathogen at Wei level (avoid pungent-warm; use pungent-cooling moderate formula)
Sweating Method Ma-Huang Tang (strong diaphoresis), Gui-Zhi Tang (mild diaphoresis with gruel) Yin-Qiao San (pungent-cooling releases the exterior — "treating the upper burner as light as a feather")
Fluid Generation Mostly sweet‑warm (Gan-Cao, Gan-Jiang, Da-Zao) Mostly sweet‑cold (Mai-Dong, Sheng-Di, Sha-Shen)
Seasonal Awareness Cold damage is the origin of all diseases — no seasonal distinction Seasonal warm diseases differ (Spring → Wind‑Warmth / Summer → Summer‑Heat / Autumn → Dryness / Winter → Winter‑Warmth)
Mutual Critique Criticises the Warm-Disease School for "over‑cooling, trapping the pathogen deep" Criticises the Classic‑Formula School for "adding fuel to the fire, raising a banner for the enemy"
Warm Disease vs Cold Damage Warm disease is a sub‑category of cold damage Warm disease is a supplement to cold damage, filling gaps the Six Meridians left unaddressed

🔥 One‑Line Summary

Ni Haixia’s focus is on "the exit route of the pathogen"; Wu Jutong’s focus is on "the preservation of the body fluids".

One drives out evil; the other protects the fluids. Used together in clinical practice, they provide a dual perspective.

💡 Usage Tip

You can load both Skills simultaneously:

```
[user]
Summer high fever 39.2°C, slight aversion to cold, sore throat, thirst, floating/rapid pulse. Please prescribe.

[nihaixia skill] → Taiyang‑Yangming combination → Ge-Gen Tang
[wujutong skill] → Upper Burner, Taiyin, Wei level → Yin-Qiao San
[AI prompt to user] → The two formulas are very different. Please tell us the patient’s constitution (fluid-deficient vs robust) and the course of disease (early stage vs already 3 days) before choosing.
```

---

📂 Directory Structure

```
Master of the Warm Disease School Wu Jutong/
├── SKILL.md                    # Main router (359 lines · 13 chapters)
├── README.md                   # This file
├── CHANGELOG.md                # Version history
│
├── modules/                    # Primary source texts (5 works by Wu Jutong)
│   ├── 00_index.md
│   ├── 溫病條辨.txt            # Sanjiao differentiation outline
│   ├── 醫醫病書.txt            # Wu Jutong's miscellaneous essays (academic critique)
│   ├── 吳鞠通醫案.txt          # Raw data of 359 cases ⭐
│   ├── 溫熱經緯（吳鞠通注）.txt  # Wu Jutong's annotations
│   └── 溫病补充.txt             # Seasonal classification of warm diseases + 70+ formulas
│
├── references/                 # Secondary/Tertiary analysis (13 papers)
│   ├── 01-core-philosophy.md       Core philosophy (Sanjiao + Wei‑Qi‑Ying‑Blood)
│   ├── 02-decision-heuristics.md   Decision heuristics (22 principles)
│   ├── 03-expression-dna.md        Expression DNA (Wu Jutong's linguistic style)
│   ├── 04-antipatterns-boundaries.md  Antipatterns & boundaries (prohibited interventions)
│   ├── 05-biography-legacy.md      Biography & school lineage
│   ├── 06-tensions.md              6 internal tensions (preserving contradictions, not reconciling them)
│   ├── 07-intellectual-lineage.md  Intellectual lineage (influences & legacy)
│   ├── 08-faq.md                   12 FAQs (covering 4 categories)
│   ├── 09-clinical-safety.md       Clinical safety (5 lethal pathways + 31 rules) ⭐
│   ├── 24-formula-pattern-system.md  Formula–pattern system (22 formulas)
│   ├── 28-wenbing-classification.md  Quick warm‑disease classification (8 seasonal types)
│   ├── 29-diagnostic-formulas.md   9 core diagnostic formulas ⭐
│   └── 30-modern-diseases.md       Historical–modern disease mapping (40+ modern diseases)
│
├── cases/                      # 359 medical cases ⭐⭐⭐
│   ├── _index.md               # Master index (by volume + pattern, 811 lines)
│   ├── _quick-lookup.md        # Quick‑lookup index (4 dimensions: pathogenesis/Sanjiao/formula/symptom)
│   ├── Wind-Warmth/案001.md
│   ├── Warm-Epidemic/案001.md ... 案023.md
│   ├── Summer-Heat/案001.md ... 案013.md
│   ├── ... (45 pattern subdirectories in total)
│   └── Phlegm-Retention/案001.md ... 案031.md
│
└── outputs/                    # Distillation stage outputs
    ├── 100questions.md         # 100‑question test set
    ├── 100answers/             # AI‑generated answers (100 questions × 24 sub‑volumes)
    │   └── Q01-季节性养生01.md ... Q21-Q40.md ... Q81-Q100.md
    └── cover-report.md         # Scoring report for the 100 questions
```

---

🩺 Sanjiao Differentiation: The Core Framework

Wu Jutong established the Sanjiao as the outline, Wei‑Qi‑Ying‑Blood as the sub‑categories dual‑layer diagnostic system at the very beginning of the Systematized Identification of Warm Diseases:

Sanjiao (Disease Location)

Burner Viscera Typical Symptoms Representative Formula
Upper Lung / Pericardium Fever, cough, sore throat, delirium Yin-Qiao San, Sang-Ju Yin, An-Gong Niu-Huang Wan
Middle Spleen/Stomach / Large Intestine High fever, intense thirst, profuse sweating, constipation Bai-Hu Tang, Cheng-Qi formulas, Zeng-Ye Tang
Lower Liver / Kidney Convulsions, urinary retention, collapse Fu-Mai Tang, San-Jia Fu-Mai, Qing-Hao Bie-Jia Tang

Wei‑Qi‑Ying‑Blood (Disease Stage)

Level Location Diagnostic Key Points Representative Formula
Wei Lung/Defence Fever with slight chill, thin white tongue coating Yin-Qiao San
Qi Lung/Stomach/Intestines High fever, intense thirst, profuse sweating, surging pulse Bai-Hu Tang, Cheng-Qi formulas
Ying Pericardium Crimson tongue, restlessness, faint macules Qing-Ying Tang, An-Gong Niu-Huang Wan
Xue Liver/Kidney Macules, bleeding, convulsions Xi-Jiao Di-Huang Tang, Ling-Jiao Gou-Teng Tang

Transmission Patterns

Progressive transmission: Upper Burner → Middle Burner → Lower Burner (Wei→Qi→Ying→Xue) — gradual worsening

Retrograde transmission: from Lung/Defence directly to Pericardium (Wei level → Ying level) — critical and dangerous (Wu Jutong coined the concept of "retrograde invasion of the Pericardium")

---

💊 Quick Formula Reference (22 Core Formulas by Burner)

Upper Burner · Pungent‑Cooling 3‑Stage

Severity Formula Indications Key Herbs
Mildest Sang-Ju Yin Only cough, not very hot, slight thirst Sang-Ye, Ju-Hua, Xing-Ren
Moderate Yin-Qiao San Fever with slight chill, sore throat Jin-Hua, Lian-Qiao, Bo-He
Severe Bai-Hu Tang High fever, intense thirst, profuse sweating, surging pulse Shi-Gao, Zhi-Mu, Gan-Cao, Jing-Mi

Upper Burner · Cool‑Opening Three Treasures

Formula Indication Feature
An-Gong Niu-Huang Wan High fever, delirium Most cooling; excels in clearing heat and detoxifying
Zi-Xue Dan High fever, convulsions, constipation Excels in calming convulsions and extinguishing wind
Zhi-Bao Dan Phlegm clouding, deep coma Excels in resolving turbidity and opening the orifices

Middle Burner · Clearing and Purging

Formula Indication Key
Bai-Hu Tang Qi‑level intense heat "Four Greats" (high fever, intense thirst, profuse sweating, surging pulse)
Cheng-Qi formulas Fu‑organ excess with constipation Da-Cheng-Qi, Xiao-Cheng-Qi, Tiao-Wei-Cheng-Qi, Zeng-Ye-Cheng-Qi
Zeng-Ye Tang Fluid‑deficient constipation Xuan-Shen, Mai-Dong, Sheng-Di

Lower Burner · Nourish Yin and Subdue Yang

Formula Indication Key
Fu-Mai Tang Pathogen diminished, deficiency predominates Zhi-Gan-Cao, Sheng-Di, Mai-Dong, E-Jiao
San-Jia Fu-Mai Tang Convulsions Fu-Mai Tang + Mu-Li, Bie-Jia, Gui-Ban
Qing-Hao Bie-Jia Tang Evening fever with morning remission Qing-Hao, Bie-Jia, Sheng-Di, Zhi-Mu, Dan-Pi

Full formula system at references/24-formula-pattern-system.md

---

📚 Medical Case Library (45 Patterns · 359 Cases)

Pattern Distribution by Category

Category Patterns Cases Examples
Warm Diseases (Wei‑Qi‑Ying‑Blood / Sanjiao transmission) 7 81 Wind‑Warmth, Warm Epidemic, Summer‑Heat, Latent Summer‑Heat, Warm Toxin, Damp‑Warmth, Winter‑Warmth
Internal Miscellaneous (Zang‑Fu differentiation) 32 212 Exhaustion, Haemoptysis, Swelling, Mania, Abdominal masses...
External / ENT 2 10 Lung abscess, Sore throat
Infectious / Exogenous 3 39 Malaria, Cold damage, Dryness
Paediatrics 1 17 Smallpox
Total 45 359 —

🔍 4‑Dimensional Quick‑Lookup Index (_quick-lookup.md)

When the AI receives a case, it first locks onto the symptoms/pathogenesis/therapeutic method, then cross‑references the corresponding cases:

1. Pathogenesis / Therapeutic Method dimension (26 categories) — e.g., "pungent‑cooling release exterior → Wind‑Warmth / Warm Epidemic / Winter‑Warmth = 36 cases"

2. Sanjiao / Wei‑Qi‑Ying‑Blood dimension (4 major locations) — e.g., "Upper Burner warm diseases = 74 cases", "Lower Burner warm diseases = 125 cases"

3. High‑frequency formulas reverse index (30 formulas) — e.g., "Bai-Hu Tang → Summer‑Heat / Latent Summer‑Heat / Wind‑Warmth / Warm Epidemic = 60 cases", "Yin-Qiao San → Wind‑Warmth / Warm Epidemic / Winter‑Warmth = 36 cases"

4. Chief complaint / symptom dimension (16 types) — e.g., "Fever / thirst → Wind‑Warmth / Summer‑Heat / Warm Epidemic / Latent Summer‑Heat / Winter‑Warmth = 64 cases", "Delirium / convulsions → Warm Epidemic / Wind‑Warmth / Summer‑Heat = 59 cases"

Full index at cases/_quick-lookup.md
Full pattern table at cases/_index.md

---

🛡️ Clinical Safety Layer (5 Lethal Pathways + 31 Immutable Rules)

⚠️ Five Lethal Pathways of Warm Diseases (Warning Signs of Depletion of the Source of Transformation)

Wu Jutong’s most emphasised clinical warnings:

1. Lung's source of transformation depleted: Lung Qi scorched, fluids exhausted → panting and collapse
2. Heart's source of transformation depleted: Heat entrapping the Pericardium, delirium, Yin fluids consumed
3. Liver's source of transformation depleted: Liver wind stirring internally, convulsions, fatigue and spasms
4. Spleen's source of transformation depleted: Spleen Yin dried up, middle Qi depleted
5. Kidney's source of transformation depleted: Kidney Yin dried up, deficient wind stirring internally

🚫 Four Prohibitions of Bai-Hu Tang (floating/sinewy/thready pulse, sunken pulse, no thirst, no sweating)

"Bai-Hu Tang is the main formula for clearing Qi‑level intense heat in warm diseases, but using it incorrectly kills people."

Wu Jutong established these prohibitions in Systematized Identification of Warm Diseases, Upper Burner chapter, item 9.

🚫 Three Prohibitions for Damp‑Warmth

1. No sweating (dampness patients avoid sweating; sweating leads to convulsions)
2. No purging (damp‑warmth that has not transformed into dryness should not be purged; purging leads to diarrhoea)
3. No moistening (damp‑warmth that has not transformed into heat should not be moistened; moistening makes the disease deep and unresolved)

📜 31 Immutable Therapeutic Rules

Detailed 26 emergency formulas for iatrogenic mistreatment + 5 lethal pathways + 31 rules at references/09-clinical-safety.md

---

🎭 Role‑Play Examples

Example 1: Upper Burner Warm Disease (Early Spring Wind‑Warmth)

【User】 Female, 28 years old, caught a chill in early March, fever 38.7°C, slight aversion to cold, sore throat for 1 day, slight thirst, red tongue tip, floating/rapid pulse. Should we use Ma-Huang Tang from the classic school, or Yin-Qiao San from the seasonal school?

【Wu Jutong · Skill】

The disease is in the Upper Burner, Hand Taiyin, Lung–Wei level. Early spring Wind‑Warmth — it is not Cold Damage.

· Cold Damage: floating/tight pulse, severe aversion to cold, no sweating, wheezing → Ma-Huang Tang (pungent‑warm sweating)
· Wind‑Warmth: floating/rapid pulse, sore throat, thirst → Yin-Qiao San (pungent‑cooling moderate formula)

This case has floating/rapid pulse + sore throat + thirst — all three are present, so Wind‑Warmth is beyond doubt. Ma-Huang Tang would "add fuel to the fire and raise a banner for the enemy" — contraindicated.

Prescribe Yin-Qiao San with modifications:

· Jin-Hua 30g, Lian-Qiao 30g (pungent‑cooling clear heat)
· Bo-He 18g, added later (pungent‑cooling release the exterior)
· Jie-Geng 18g, Sheng-Gan-Cao 15g (benefit the throat and detoxify)
· Niu-Bang-Zi 18g, Dan-Dou-Chi 15g (release exterior and benefit the throat)
· Lu-Gen 30g (generate fluids)

If no improvement after 3 days, advance to Bai-Hu Tang ("treating the upper burner requires lightness — but Bai-Hu Tang is powerful and should only be used if Yin-Qiao fails"). Keep the Four Prohibitions of Bai-Hu Tang in mind: floating/sinewy/thready pulse, sunken pulse, no thirst, no sweating — if any one is present, Bai-Hu Tang is forbidden.

Example 2: Cross‑School Comparison

【User】 For the same case, how would Ni Haixia prescribe?

【Ni Haixia · Skill】 (loaded concurrently)

Six‑Meridian differentiation: Taiyang–Yangming combination. Floating/rapid pulse = Taiyang not yet resolved; thirst and sore throat = Yangming internal heat already arising.

Prescribe Ge-Gen Tang: Ge-Gen, Ma-Huang, Gui-Zhi, Bai-Shao, Gan-Cao, Da-Zao, Sheng-Jiang.

A mild sweat will resolve Taiyang, and Yangming will descend as well (Ge-Gen specifically resolves Yangming meridian heat).

Note: Ni Haixia believes that the early stage of warm diseases can still be treated with Ge-Gen Tang to release the muscles — this represents a fundamental divergence from Wu Jutong's "avoid sweating" position. Ni holds that "sweating out the heat" gives the pathogen an exit, while Wu holds that "sweating depletes fluids and fuels the heat."

---

📊 Version History

Version Date Theme Files
V1.0 2026-08-09 AM Initial distillation (10 references + 255-line SKILL.md) —
V2.0 2026-08-09 Midday Structured additions (6 major modules) CHANGELOG.md §V2.0
V3.0 2026-08-09 PM Three optimisations (diagnostic formulas + modern disease mapping + cross‑school compatibility) CHANGELOG.md §V3.0
V3.1 2026-08-09 Evening 10‑dimensional Classic vs Warm‑Disease comparison + cases library (359 cases · dual index) CHANGELOG.md §V3.1

Full changelog at CHANGELOG.md

---

🙏 Acknowledgements & Sources

Primary Sources (Wu Jutong's Works)

· Systematized Identification of Warm Diseases (1798) — Sanjiao differentiation outline
· Medical Essays on Healing — Wu Jutong’s miscellaneous essays
· Wu Jutong's Medical Cases — 359 clinical cases
· Annotations on Exegesis of the Warm and Heat Classics — Wu Jutong’s critical commentaries
· Supplement on Warm Diseases — seasonal classification

Distillation Methodology

· Base method: TCM Thought Distiller V3.5
· Cross‑school testing: Co‑tested with jangviktor-web/nihaixia (Ni Haixia Classic‑Formula School Skill)

Secondary/Tertiary References

· Jin Yuesheng’s compilation of Wu Jutong's Medical Cases in five volumes (Wu Jutong’s disciple)
· Cao Bingzhang’s annotations
· Wikisource digitisation

Citation

Based on the works of Wu Jutong (1758–1836) of the Warm Disease School, distilled by jangviktor-web/wujutong V3.1

---

⚠️ Disclaimer

This Skill is intended for educational and academic research purposes only. It does not provide medical diagnosis, prescriptions, or individualised treatment advice.

1. The AI’s responses are based on historical texts and simulated thought processes — they cannot replace the clinical judgment of a licensed TCM practitioner.
2. TCM emphasises pattern differentiation. The formulas suggested by this Skill are only illustrations of Wu Jutong’s reasoning; actual clinical application must account for the individual patient’s condition.
3. Warm diseases can progress rapidly. If you suspect a warm disease, seek medical attention immediately — do not rely on AI‑generated prescriptions.
4. For pregnant women, children, the elderly, and those with chronic diseases, always consult a qualified physician.

The project authors assume no responsibility for any clinical consequences arising from the use of this Skill.

---

📄 License

This project is licensed under the MIT License — see the LICENSE file.

```
MIT License

Copyright (c) 2026 jangviktor-web

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to furnish persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

📮 Feedback & Contributions

· GitHub Issues: github.com/jangviktor-web/wujutong/issues
· Companion Skill: nihaixia (Ni Haixia · Classic‑Formula School)

---

"Discernment is not a matter of labels — read many ancient books and observe the changes of the times." — Preface to Wu Jutong's Medical Cases

Last updated: 2026-08-09

</div>