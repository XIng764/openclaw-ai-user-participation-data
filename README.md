# OpenClaw AI User Participation Data

This repository provides English-language survey workbooks used in the study **CAIP: A Statistical Analysis Framework for OpenClaw User Behavior**. The study examines how cognition, affect, information cascades, and participation relate in an OpenClaw user context.

The accompanying paper uses the **CAIP** framework:

- **Cognition**: self-reported knowledge of OpenClaw and AI-use frequency.
- **Affect**: AI-related anxiety and associated perceptions.
- **Information Cascade**: external public narratives and social signals surrounding AI.
- **Participation**: continued use, recommendation, and herding-related intentions.

## Data files

| File | Description |
| --- | --- |
| OpenClaw_AI_User_Participation_Survey_Scores_EN.xlsx | Numeric-coded survey workbook with English variable names and value labels. |
| OpenClaw_AI_User_Participation_Survey_Text_EN.xlsx | Text-response survey workbook with English variable names and translated non-numeric responses. |

Both workbooks contain **500 valid survey records**. The English versions translate the original Chinese indicators, response labels, and other non-numeric text; numeric values are retained as provided.

## Study design

The paper combines two complementary sources of evidence:

1. A survey of OpenClaw users, used for descriptive statistics, reliability and validity checks, K-means clustering, association-rule analysis, and logistic regression.
2. A separately collected public-news corpus, used to describe AI-related social narratives through dictionary-based text coding.

The two sources are interpreted as complementary evidence. They are not linked at the individual level and should not be treated as proof of causal effects.

## Main variables

The survey includes demographic fields and 1-5 Likert-scale measures covering:

- social influence;
- hedonic motivation;
- anthropomorphic perception;
- performance expectation;
- perceived ease and control;
- behavioral resistance;
- emotional anxiety; and
- participation or herding-related tendency.

Self-reported OpenClaw knowledge and AI-use frequency are used to characterize user groups. In the paper, the main logistic-regression outcome is a binary high-anxiety indicator defined using the sample median.

## Reported findings

The paper reports three cognition/use-frequency clusters. The low-knowledge, high-frequency group accounts for 201 of 500 respondents (40.2%) and has higher mean anxiety and herding-tendency scores than the high-knowledge, relatively high-frequency group.

In the reported main-effects logistic model, anthropomorphic perception, hedonic motivation, and perceived ease/control are positively associated with the high-anxiety indicator. These are exploratory associations, not causal estimates. The paper also notes measurement-reliability and model-validation limitations that should be considered before reusing or generalizing the results.

## Responsible use

Use the data for research, teaching, or non-commercial analytical purposes only. Do not attempt to identify individual respondents. The workbooks may contain administrative metadata, including IP-derived regional labels; users are responsible for complying with applicable privacy, ethics, and data-protection requirements before redistribution or analysis.

## Citation

If you use these materials, please cite the accompanying study:

> Zhang Yihang, Zhao Hongkai, and Zhu Bao. *CAIP: A Statistical Analysis Framework for OpenClaw User Behavior.* Wuxi University, Wuxi, Jiangsu, China.

## Notes

- All translated labels are provided for accessibility and analysis convenience.
- The original Chinese workbooks remain in the local project archive and are not part of this repository release.
- The repository currently contains the translated survey workbooks; the public-news corpus and reproduction materials described in the paper are not included here.
