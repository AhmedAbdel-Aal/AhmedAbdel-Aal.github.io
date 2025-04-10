---
title: 'mucAI at WojoodNER 2024: Arabic Named Entity Recognition with Nearest Neighbor Search'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tasneem Mahmoud

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Second Arabic Natural Language Processing Conference*
publication_short: In *Arabic NLP 24 - ACL*

abstract: Named Entity Recognition (NER) is a task in Natural Language Processing (NLP) that aims to identify and classify entities in text into predefined categories.However, when applied to Arabic data, NER encounters unique challenges stemming from the language’s rich morphological inflections, absence of capitalization cues, and spelling variants, where a single word can comprise multiple morphemes.In this paper, we introduce Arabic KNN-NER, our submission to the Wojood NER Shared Task 2024 (ArabicNLP 2024). We have participated in the shared sub-task 1 Flat NER. In this shared sub-task, we tackle fine-grained flat-entity recognition for Arabic text, where we identify a single main entity and possibly zero or multiple sub-entities for each word.Arabic KNN-NER augments the probability distribution of a fine-tuned model with another label probability distribution derived from performing a KNN search over the cached training data. Our submission achieved 91% on the test set on the WojoodFine dataset, placing Arabic KNN-NER on top of the leaderboard for the shared task.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Arabic NLP
  - NER

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.arabicnlp-1.107/'
url_code: 'https://github.com/AhmedAbdel-Aal/WNER_24_sharedtask'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://www.youtube.com/watch?v=HUHD3Lwud68'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Authors**](https://aclanthology.org/2024.arabicnlp-1.107/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---