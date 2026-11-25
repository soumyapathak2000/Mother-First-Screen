# Mother-First Screen

**A community-based perinatal depression screening and referral system for rural and semi-urban India**

Project for the *AI Careers for Women* LinkedIn Fellowship 2.0 (Edunet Foundation, with Microsoft, LinkedIn, SAP and IISc).

> **Status: design stage / work in progress.** This is a student project. It is not a clinical tool, it has not been clinically validated, and **no real participant data is used anywhere in this repository.**

## The problem

Many pregnant women and new mothers in rural and semi-urban India experience depression and anxiety that go unrecognised. Routine maternal care focuses on physical health, stigma discourages women from speaking up, specialists are concentrated in cities, and there is rarely a tracked path from a positive screen to care.

## The idea

ASHA and ANM workers, who already visit pregnant women and new mothers, screen them with the **Edinburgh Postnatal Depression Scale (EPDS)** in the local language. Scoring follows a fixed rule (**no AI is used to screen or diagnose**). Any woman who scores at or above the cut-off, or who answers the self-harm item, is referred to the PHC medical officer and given the **Tele-MANAS helpline (14416)**. Supervisors see anonymised counts in a Power BI dashboard.

**Screening is not diagnosis.** The toolkit screens and refers.

## What is in this repository

| Folder / file | What it contains |
|---|---|
| `Project_Synopsis_Mother_First_Screen.docx` | Project synopsis (AICW template) |
| `October_Report_AICW.docx` | October month project report |
| `dataset/synthetic_screening_data_raw.csv` | Fully synthetic, deliberately messy screening records (for practising cleaning and dashboards) |
| `dataset/DATA_DICTIONARY.md` | Field descriptions and the known data problems |
| `knowledge_base/references.md` | Research sources with links and what each supports |
| `knowledge_base/screening_and_referral_protocol.md` | Draft screening and referral flow |
| `knowledge_base/ethics_and_responsible_use.md` | Ethics and responsible AI use notes |

## Approach in four steps

1. **Screen (no AI):** EPDS in the local language, with audio instructions, using an offline-friendly form (KoboToolbox or Google Forms).
2. **Refer:** PHC medical officer and Tele-MANAS 14416 for every at-or-above-cut-off result and every self-harm answer.
3. **Monitor:** Clean the data in Excel (Power Query) and show it in a Power BI dashboard (aggregate counts only).
4. **Support (generative AI, human-checked):** Draft awareness scripts and plain-language summaries, always reviewed by a person.

## Tools

KoboToolbox / Google Forms, Microsoft Excel and Power Query, Power BI Desktop, Canva, a generative AI assistant (support role only), GitHub.

## Sustainable Development Goals

SDG 3 (Good Health and Well-being) as the primary goal, and SDG 5 (Gender Equality) as the secondary goal.

## Responsible use

- The dataset is **synthetic**. Any resemblance to real people or villages is accidental.
- The cut-off of 10 in the dataset is a **placeholder**. A validated local cut-off must be used in any real setting.
- The EPDS questions are not reproduced here. Please use a licensed, validated local-language version.
- Ethics clearance and health department permission are required before any real data collection.

## Author

Soumya Pathak, Assistant Professor of Psychology, ITM University, Raipur.
