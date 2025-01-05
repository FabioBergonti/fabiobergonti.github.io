---
title: 'Momentum-Based Extended Kalman Filter for Thrust Estimation on Flying Multibody Robots'

# Authors
# If you created a profile for a user (e.g. the default `Gabriele Nava` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hosameldin Awadalla Omer Mohamed
  - Gabriele Nava
  - Giuseppe L’Erario
  - Silvio Traversaro
  - admin
  - Luca Fiorio
  - Punith Reddy Vanteddu
  - Francesco Braghin
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  IEEE Robotics and Automation Letters
# publication_short: In *ICRA*

abstract: > 
  Effective control design of flying vehicles requires a reliable estimation of the propellers’ thrust forces to secure a successful flight. Direct measurements of thrust forces, however, are seldom available in practice and on-line thrust estimation usually follows from the application of fusion algorithms that process on-board sensor data. This letter proposes a framework for the estimation of the thrust intensities on flying multibody systems that are not equipped with sensors for direct thrust measurement. The key ingredient of the proposed framework is the so-called centroidal momentum of a multibody system, which combined with the propeller model. It enables the design of Extended Kalman Filters (EKF) for on-line thrust estimation. The presented approach tackles the additional complexity in thrust estimation due to the possibly large number of degrees of freedom of the system and uncertainties in the propeller model. For instance, a covariance scheduling approach based on the turbines RPM error is proposed to ensure a reliable estimation even in case of turbine failures. Simulations are presented to validate the proposed algorithm during robot flight. Moreover, an experimental setup is designed to evaluate the accuracy of the estimation algorithm using iRonCub, a jet-powered humanoid robot, while standing on the ground.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9622189'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://ieeexplore.ieee.org/document/9622189/media#media'

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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
