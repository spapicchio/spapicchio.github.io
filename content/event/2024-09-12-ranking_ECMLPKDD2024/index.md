---
title: 'Intersectional fair ranking via subgroup divergence'


event: ECML/PKDD 2024
event_url: https://ecmlpkdd.org/2024/

location: ECML/PKDD 2024
address:
  city: Vilnius, Lithuania

summary: Paper presentation of our intersectional fair ranking approach' 
abstract: 'Societal biases encoded in real-world data can contaminate algorithmic decisions, perpetuating preexisting inequalities in domains such as employment and education. In the fair ranking literature, following the doctrine of affirmative action, fairness is enforced by means of a group-fairness constraint requiring “enough” individuals from protected groups in the top-k positions, for a ranking to be considered valid. However, which are the groups that need to be protected? And how much representation is “enough”? As the biases affecting the process may not always be directly observable nor measurable, these questions might be hard to answer in a principled way, especially when many different potentially discriminated subgroups exist. This paper addresses this issue by automatically identifying the disadvantaged groups in the data and mitigating their disparate representation in the final ranking. Our proposal leverages the notion of divergence to automatically identify which subgroups, defined as combination of sensitive attributes, show a statistically significant deviation, in terms of ranking utility, compared to the overall population. Subgroups with negative divergence experience a disadvantage. We formulate the problem of re-ranking instances to maximize the minimum subgroup divergence, while maintaining the new ranking as close as possible to the original one. We develop a method which is based on identifying the divergent subgroups and applying a re-ranking procedure which is monotonic w.r.t. the goal of maximizing the minimum divergence. Our experimental results show that our method effectively eliminates the existence of disadvantaged subgroups while producing rankings which are very close to the original ones.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-12T11:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-12T00:00:00Z'

authors: [Eliana Pastor, Francesco Bonchi]
tags: ['ranking', 'subgroup']

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
url_pdf: 'https://link.springer.com/article/10.1007/s10618-024-01029-8'
url_slides: 'ecml-pkdd-pastor-ranking.pdf'


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
