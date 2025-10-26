---
title: "De-identifying student personally identifying information in discussion forum posts with large language models"
collection: publications
category: manuscripts
permalink: /publication/2025-de-identification-journal
excerpt: 'This study evaluates the effectiveness of three large language models (LLMs)—GPT-4o, Llama 3.3 70B, and Llama 3.1 8B—in redacting personally identifying information (PII) from forum data in massive open online courses (MOOCs). All models achieved an average recall above 0.9, successfully identifying most PII and even detecting instances overlooked by humans; however, their precision was lower—0.579 for GPT-4o, 0.506 for Llama 3.3, and 0.262 for Llama 3.1—indicating a tendency to over-redact non-PII text such as names and locations.'
date: 2025-04-07
venue: 'Information and Learning Sciences'
paperurl: 'https://www.emerald.com/ils/article/126/5-6/401/1246753/De-identifying-student-personally-identifying'
citation: 'Zambrano, A.F., Singhal, S., Pankiewicz, M., Baker, R.S., Porter, C., Liu, X. (2025). &quot;De-identifying student personally identifying information in discussion forum posts with large language models.&quot; <i>Information and Learning Sciences</i>. Vol. 126 No. 5-6 pp. 401–424, https://doi.org/10.1108/ILS-11-2024-0156.'
---

**Purpose**

This study aims to evaluate the effectiveness of three large language models (LLMs), GPT-4o, Llama 3.3 70B, and Llama 3.1 8B, in redacting personally identifying information (PII) from forum data in massive open online courses (MOOCs).

**Design/methodology/approach**

Forum posts from students enrolled in nine MOOCs were redacted by three human reviewers. The GPT and Llama models were then tasked with de-identifying the same data set using standardized prompts. Discrepancies between LLM and human redactions were analyzed to identify patterns in LLM errors.

**Findings**

All models achieved an average recall of over 0.9 in identifying PII and identified PII instances overlooked by humans. However, their precisions were lower – 0.579 for GPT-4o, 0.506 for Llama 3.3, and 0.262 for Llama 3.1 – showing a tendency to over-redact non-PII names and locations.

**Research limitations/implications**

Several courses’ data were analyzed to increase the generalizability of findings, but the models’ performance may vary in other contexts. GPT and Llama models were selected because of their availability and cost-effectiveness at the time of the study; future newer models may improve performance.

**Practical implications**

The use of downloadable LLMs enables researchers to de-identify data without training specialized models or involving external companies, ensuring that student data remains private.

**Originality/value**

Previous research on LLM text de-identification has largely used proprietary models, which require sharing data containing sensitive PII with third-party companies. This study evaluates the performance of two open weight models that can be deployed locally, eliminating the need to share sensitive data externally.

