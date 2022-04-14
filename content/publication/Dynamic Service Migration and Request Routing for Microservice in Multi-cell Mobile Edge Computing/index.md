---
title: "Dynamic Service Migration and Request Routing for Microservice in Multi-cell Mobile Edge Computing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yuanguo Bi

date: "2022-01-04T00:00:00Z"
doi: "10.1109/JIOT.2022.3140183"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Internet of Things Journal *
publication_short: In *IoT*

abstract: Mobile Edge Computing (MEC) sinks computation and storage capacities to network edge, where it is close to users to support delay-sensitive services. However, due to the dynamic and stochastic properties of MEC networks, the deployed services may be frequently migrated among edge servers to follow the mobility of users, which greatly increases the network operational cost. In this paper, considering the service migration cost brought by user mobility, we study the joint optimization problem of service deployment and request routing decisions to maximize the long-term network utility of MEC networks. Firstly, we propose a Lyapunov optimization-based online service migration algorithm to decompose the continuous optimization problem into a number of one-slot online optimization problems. Then, to address the NP-hard issue of one-slot optimization, we use a randomized rounding technique to implement service migration and request routing. Furthermore, through a closed-form theoretical analysis, we prove that the proposed algorithm not only greatly meets the local user requests and enables approximate performance guarantees, but also adaptively balances the service migration cost and system performance online. Finally, extensive simulations are conducted, which demonstrate that our algorithm can efficiently utilize the storage and computation resources of edge servers, and maximize the long-term network utility while ensuring the stability of service migration cost.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

