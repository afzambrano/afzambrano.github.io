---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a doctoral candidate at the University of Pennsylvania and a Fulbright Scholar, with a research trajectory focused on the intersection of education, artificial intelligence, and machine learning.

My work centers on the development of machine learning models capable of detecting affective states and behavioral patterns across diverse educational platforms, with the goal of enhancing the personalization, equity, and effectiveness of digital learning.

My primary line of research explores educational video games, investigating how interactive environments (such as Minecraft and other open-world games) can foster science learning and teaching through immersive and engaging experiences.

In addition, I study how language models can be used to design pedagogical interventions within classrooms and to support qualitative research.

A key component of my work also involves the analysis of algorithmic bias, aiming to design artificial intelligence systems that operate in a fair, inclusive, and representative manner for students from diverse backgrounds and demographics.

I am an active participant in international conferences such as Educational Data Mining (EDM), Quantitative Ethnography (ICQE), Learning Analytics and Knowledge (LAK), and Artificial Intelligence in Education (AIED).

Selected Publications
======
[Publication 1](https://www.mathjax.org/)
------
Abstract

[De-identifying student personally identifying information in discussion forum posts with large language models](https://www.emerald.com/ils/article/126/5-6/401/1246753/De-identifying-student-personally-identifying)
------

Previous research on LLM text de-identification has largely used proprietary models, which require sharing data containing sensitive PII with third-party companies. This study evaluates the performance of two open weight models that can be deployed locally, eliminating the need to share sensitive data externally. This study aims to evaluate the effectiveness of three large language models (LLMs), GPT-4o, Llama 3.3 70B and Llama 3.1 8B, in redacting personally identifying information (PII) from forum data in massive open online courses (MOOCs). Forum posts from students enrolled in nine MOOCs were redacted by three human reviewers. The GPT and Llama models were then tasked with de-identifying the same data set using standardized prompts. Discrepancies between LLM and human redactions were analyzed to identify patterns in LLM errors. All models achieved an average recall of over 0.9 in identifying PII and identified PII instances overlooked by humans. However, their precisions were lower – 0.579 for GPT-4o, 0.506 for Llama 3.3 and 0.262 for Llama 3.1 – showing a tendency to over-redact non-PII names and locations. Several courses’ data were analyzed to increase findings’ generalizability but the models’ performance may vary in other contexts. GPT and Llama models were selected because of their availability and cost-effectiveness at the time of the study; future newer models may improve performance. The use of downloadable LLMs enables researchers to de-identify data without training specialized models or involving external companies, ensuring that student data remains private.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
