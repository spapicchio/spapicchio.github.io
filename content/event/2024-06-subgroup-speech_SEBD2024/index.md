---
title: 'Assessing Speech Model Performance: A Subgroup Perspective'


event: SEBD 2024
event_url: https://sebd2024.unica.it/

location: SEBD 2024
address:
  city: Villasimius, Italy

summary: Paper presentation of our works on assessing speech model performance 
abstract: 'Spoken language understanding (SLU) models are commonly evaluated based on overall performance or predefined subgroups, often overlooking the potential insights gained from more comprehensive subgroup analyses. Conducting a more thorough analysis at the subgroup level can reveal valuable insights into the variations in speech system performance across different subgroups. Yet, identifying interpretable subgroups in raw speech data poses inherent challenges. 
To overcome these issues, we enrich speech data with metadata from various domains. We consider, when available, speaker demographics like gender, age, and origin country. We also incorporate taskrelated features, such as a specific intent or emotion associated with an utterance. Finally, we extract signal-related metadata, including speaking rate, signal-to-noise ratio, number of words, and number of pauses. Including these features, extracted directly from the raw signal, is crucial in capturing fine-grained nuances that may impact model performance. By combining these metadata, we identify human-understandable subgroups in which speech models exhibit performance significantly better or worse than the average. 
Our approach is task-, model-, and dataset-agnostic. It enables the identification of intra- and crossmodel performance gaps, highlighting disparities among different models. We validate our methodology across three tasks (intent classification, automatic speech recognition, and emotion recognition), three datasets, and one speech model with different sizes, providing nuanced insights into model assessments. We further propose leveraging this approach to guide a data acquisition strategy for improved and fairer models. The experimental results demonstrate that our approach leads to substantial performance improvements and significant reductions in performance disparities, all achieved with reduced data and costs compared to random and clustering-based acquisition techniques'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-06-24T12:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-24T00:00:00Z'

authors: [Alkis Koudounas, Eliana Pastor, Elena Baralis]
tags: ['subgroup', 'speech']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ""
  focal_point: ""
  preview_only: false

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/eliana__pastor
url_pdf: 'https://ceur-ws.org/Vol-3741/paper64.pdf'
url_slides: 'subgroup-speech_SEBD2024.pdf'


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
