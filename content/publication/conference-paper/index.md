---
title: 'Data Self-Expansion and DoppelGANger-Based Time-Series Modeling for Realistic Steam Data Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)

date: '2023-04-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Power and Renewable Energy*
publication_short: In *ICPRE*

abstract: Steam heating is an essential component of numerous industrial production processes that consume energy extensively. In particular, steam data are of significant commercial interest, and the privacy of the heat suppliers and steam users for whom this data is confidential is of paramount importance. However, the complexity and intricacy of steam data make it challenging to generate realistic samples using conventional data generation algorithms. This paper proposes a self-expansion data process method that multiplies samples with a coarser granularity. We then apply the time-series generation model, DoppelGANger, to steam data. Post-processing for the generated data is implemented to eliminate the effects of a certain level of noise. To validate the proposed method and model, we conduct experiments using field data obtained from a thermopower company. The results indicate that DoppelGANger can capture the steam operating characteristics and generate realistic samples reflecting steam data patterns. The difference between the statistic metrics of the true and generated samples is around 2.87%. The mean DTW distance of features' principal components is around 16.32. Overall, this study offers a promising workflow for data generation across many steam system scenarios. This approach is valuable for energy management, privacy protection, and data sharing in industrial domains.

# Summary. An optional shortened abstract.
summary: Proposing a self-expansion method for realistic steam data generation using DoppelGANger model, benefiting energy management and privacy protection.

tags: 
- GAN
- Time-series
- Data generation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/cecicxy/steam-data-generation/blob/main/paper.pdf'
url_code: 'https://github.com/cecicxy/steam-data-generation/tree/main/model'
url_dataset: 'https://github.com/cecicxy/steam-data-generation/tree/main/data'
url_source: 'https://github.com/cecicxy/steam-data-generation'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

