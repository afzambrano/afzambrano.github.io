---
title: "Towards Generalizable Detection of Urgency of Discussion Forum Posts"
collection: publications
category: conferences
permalink: /publication/2023-edm-urgency-posts
excerpt: 'This study develops predictive models to automatically assess the urgency of discussion forum posts in MOOCs on a 7-point scale, helping instructors prioritize student support more efficiently. Using data from MOOCs at the University of Pennsylvania and Stanford University, a support vector regressor trained on Universal Sentence Encoder embeddings achieved the best performance, demonstrating strong generalizability across institutions.'
date: 2023-07-14
venue: 'Educational Data Mining'
paperurl: 'https://educationaldatamining.org/edm2023/proceedings/2023.EDM-short-papers.29/index.html'
---

Students who take an online course, such as a MOOC, use the course's discussion forum to ask questions or reach out to instructors when encountering an issue. However, reading and responding to students' questions is difficult to scale because of the time needed to consider each message. As a result, critical issues may be left unresolved, and students may lose the motivation to continue in the course. To help address this problem, we build predictive models that automatically determine the urgency of each forum post, so that these posts can be brought to instructors' attention. This paper goes beyond previous work by predicting not just a binary decision cut-off but a post's level of urgency on a 7-point scale. First, we train and cross-validate several models on an original data set of 3,503 posts from MOOCs at University of Pennsylvania. Second, to determine the generalizability of our models, we test their performance on a separate, previously published data set of 29,604 posts from MOOCs at Stanford University. While the previous work on post urgency used only one data set, we evaluated the prediction across different data sets and courses. The best-performing model was a support vector regressor trained on the Universal Sentence Encoder embeddings of the posts, achieving an RMSE of 1.1 on the training set and 1.4 on the test set. Understanding the urgency of forum posts enables instructors to focus their time more effectively and, as a result, better support student learning. 

[Download Paper](https://educationaldatamining.org/edm2023/proceedings/2023.EDM-short-papers.29/index.html)
