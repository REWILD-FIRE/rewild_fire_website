---
title: "Evaluating organic carbon in living and dead trees using GLCM features and explainable machine learning: insights from Italian national forest"
authors:
- M. Fasihi
- A.Falcon
- G.Alberti
- L.Cadez
- F.Giannetti
- A.Tomao
- G. Serra
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-06-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Annals of GIS, 1*(1)"
publication_short: ""

abstract: An accurate estimation of organic carbon (OC) in forest ecosystems is essential for understanding carbon dynamics and informing climate change mitigation strategies. This study presents a novel, explainable machine learning framework to estimate two key carbon pools: carbon sequestration in living trees (CSE) and carbon storage in standing deadwood (SDC). The methodology is structured into five key steps. First, we extract Gray-Level Co-occurrence Matrix (GLCM) texture features from LiDAR-derived canopy height models to quantify spatial heterogeneity in forest structure. Second, we integrate these GLCM metrics with vegetation indices (VIs), geomorphological variables, and weather data to create six distinct input configurations. Third, we train and evaluate teen models on each configuration to assess model performance and feature synergy. Fourth, we apply SHapley Additive exPlanations (SHAP) to the three models to transform them into an interpretable white-box model, identifying key predictors such as AVG_mean, SD_entropy, and SD_homogeneity. Finally, we assess model uncertainty using jackknife resampling and error bar analysis. The results indicate that CatBoost and Random Forest models deliver the highest performance for OC estimation. This study is the first to apply GLCM features for the joint estimation of CSE and SDC at a regional scale and to integrate explainable AI into forest carbon modelling. The framework provides a practical, transparent tool for forest managers, policymakers, and carbon monitoring systems, supporting high-resolution, scalable, and interpretable OC assessments.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
#- Organic arbon
#- carbon sequestration
#- standing deadwood
#- explainable machine learning
#- remote sensing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1080/19475683.2025.2523737
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
  caption: 'GLCM-Based organic carbon estimation and explainable ML pipeline for forest inventory data.'
  focal_point: ""
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
