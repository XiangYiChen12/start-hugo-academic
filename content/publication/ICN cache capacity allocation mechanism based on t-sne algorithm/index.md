---
title: "基于 t-SNE 算法的 ICN 缓存容量分配机制"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xingwei Wang

date: "2019-09-15T00:00:00Z"
doi: "10.13705/j.issn.1671-6841.2018331"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *郑州大学学报 (理学版)*
publication_short: 

abstract: 针对现有ICN中节点负载不均衡、重要节点缓存利用率低、缓存开销大等问题，面向互联网主干网节点，提出了基于t-SNE算法的ICN缓存容量分配机制.首先，收集网络拓扑信息和流量特征信息并建立高维数据集；然后，通过构造K-近邻表征相似性的方式改进t-SNE算法，对数据集进行降维并对网络节点进行聚类划分；最后，基于聚类结果，将有限的缓存容量合理地分配给不同节点以平衡节点负载.仿真结果表明，本设计的缓存容量分配机制和基准机制相比，在保证路由成功率维持在约95%的前提下，缓存命中率提升了3%~4%，平均缓存开销减少了13.5%~23.4%.

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

---



