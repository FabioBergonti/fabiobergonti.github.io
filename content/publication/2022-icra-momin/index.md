---
title: 'Nonlinear Model Identification and Observer Design for Thrust Estimation of Small-scale Turbojet Engines'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Affaf Junaid Ahamad Momin
  - Gabriele Nava 
  - Giuseppe L'Erario
  - Hosameldin Awadalla Omer Mohamed
  - admin
  - Punith Reddy Vanteddu
  - Francesco Braghin
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  International Conference on Robotics and Automation
# publication_short: In *ICRA*

abstract: > 
  Jet-powered vertical takeoff and landing (VTOL) drones require precise thrust estimation to ensure adequate stability margins and robust maneuvering. Small-scale turbojets have become good candidates for powering heavy aerial drones. However, due to limited instrumentation available in these turbojets, estimating the precise thrust using classical techniques is not straightforward. In this paper, we present a methodology to accurately estimate the online thrust for the small-scale turbojets used on the iRonCub - an aerial humanoid robot. We use a grey-box method to capture the turbojet system dynamics with a nonlinear state-space model based on the data acquired from a custom engine test bench. This model is then used to design an extended Kalman filter that estimates the turbojet thrust only from the angular speed measurements. We exploited the parameter estimation algorithm to ensure that the EKF gives smooth and accurate estimates even at engine failures. The designed EKF was validated on the test bench where the mean absolute error in estimated thrust was found to be within 2% of rated peak thrust.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9812283'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
