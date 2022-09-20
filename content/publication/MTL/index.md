---
title: 'Multi-task learning for data-efficient spatiotemporal
modeling of tool surface progression in ultrasonic metal welding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuhang Yang
  - Chenhui Shao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-02-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jmsy.2020.12.009'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In Journal of Manufacturing Systems
publication_short: In Journal of Manufacturing Systems

abstract: Spatiotemporal processes commonly exist in manufacturing. Modeling and monitoring such processes are crucial for ensuring high-quality production. For example, ultrasonic metal welding is an important industrial-scale joining technique with wide applications. The surfaces of ultrasonic welding tools evolve in both spatial and temporal domains, resulting in a spatiotemporal process. Close monitoring of tool surface progression is imperative since degraded tools often lead to low-quality joints. However, it is generally expensive and time-consuming to acquire fine-scale surface measurement data, which is not economically viable. This paper develops a multi-task learning method to enable data-efficient spatiotemporal modeling. A Gaussian process-based hierarchical Bayesian inference structure is constructed to transfer knowledge among multiple similar-but-not-identical measurement tasks. Meanwhile, a spatiotemporal kernel is developed based on squared sine exponential damping (SSED) function to characterize the periodic trend of anvil surfaces. The proposed method is able to improve interpolation accuracy using limited measurement data compared with state-of-the-art techniques. Data collected from lithium-ion battery production are employed to demonstrate the effectiveness of the proposed method. Additionally, the influence of training data size and hyperparameter selection on the modeling performance is systematically investigated.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
