---
title: 'Evaluating organic carbon in living and dead trees using GLCM features and explainable machine learning: insights from Italian national forest'
authors:
  - Mehdi Fasihi
  - Alex Falcon
  - Giorgio Alberti
  - Luca Cadez
  - Francesca Giannetti
  - Antonio Tomao
  - Giuseppe Serra
date: '2025-06-27T00:00:00Z'
doi: 'https://doi.org/10.1080/19475683.2025.2523737'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "Annals of GIS"
# publication_short: ""

abstract: An accurate estimation of organic carbon (OC) in forest ecosystems is essential for understanding carbon dynamics and informing climate change mitigation strategies. This study presents a novel, explainable machine learning framework to estimate two key carbon pools: carbon sequestration in living trees (CSE) and carbon storage in standing deadwood (SDC). The methodology is structured into five key steps. First, we extract Gray-Level Co-occurrence Matrix (GLCM) texture features from LiDAR-derived canopy height models to quantify spatial heterogeneity in forest structure. Second, we integrate these GLCM metrics with vegetation indices (VIs), geomorphological variables, and weather data to create six distinct input configurations. Third, we train and evaluate teen models on each configuration to assess model performance and feature synergy. Fourth, we apply SHapley Additive exPlanations (SHAP) to the three models to transform them into an interpretable white-box model, identifying key predictors such as AVG_mean, SD_entropy, and SD_homogeneity. Finally, we assess model uncertainty using jackknife resampling and error bar analysis. The results indicate that CatBoost and Random Forest models deliver the highest performance for OC estimation. This study is the first to apply GLCM features for the joint estimation of CSE and SDC at a regional scale and to integrate explainable AI into forest carbon modelling. The framework provides a practical, transparent tool for forest managers, policymakers, and carbon monitoring systems, supporting high-resolution, scalable, and interpretable OC assessments.


tags:
  - Organic carbon
  - carbon sequestration
  - standing deadwood
  - explainable machine learning
  - remote sensing
featured: true

links:
  - name: See the paper
    url: https://doi.org/10.1080/19475683.2025.2523737
    url_pdf: 'uploads/publications/Fasihi_etal_2025.pdf'

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:[]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:""
---
