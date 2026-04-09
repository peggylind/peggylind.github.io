---
title: Data Conditioning and Forecasting Methodology using Machine Learning on Production
  Data for a Well Pad

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Maryam Bagheri
- Haoran Zhao
- Manyang Sun
- Li Huang
- Srinath Madasu
- Peggy Lindner
- Giulia Toti

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-03-29T20:40:10.137345Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*OTC-30854-MS*'
publication_short: ''

hugoblox:
  ids:
    doi: 10.4043/30854-MS

abstract: Abstract A new machine learning (ML)/statistical-based methodology for conditioning
  and predicting production data for a well pad has been developed. Typically, data
  conditioning involves outlier detection, missing data, data imputation, and smoothing.
  Time-series production data prediction can be challenging because the target (wellbore
  oil production) depends on large-scale, high-dimensional data sets with unknown
  distributions and is influenced by missing data and outliers. Hence, data conditioning
  is key for accurate predictions. The current work is the first attempt at using
  ensemble ML and statistical techniques, such as multilayer perceptron (MLP), principal
  component analysis (PCA), and support vector regression (SVR), for well pad data
  conditioning using recently disclosed subsurface and production data from a field
  in the southern area of the Norwegian North Sea. The time-series forecasting based
  on large-scale, high-dimensional conditioned and cleaned data sets is also presented.
  The data with an oil production rate greater than 10 Sm3 have been retained for
  data cleansing, which reduced the size of the production well data set by 14.9%.
  Outliers are detected using the z-score method. The missing values are predicted
  using a trained ML model on all available nonmissing data. The procedure first predicts
  the downhole missing values from all the wells, including the available neighboring
  wells, and then uses these features to predict other missing values for the well
  pad. In this paper, the two approaches implemented and compared for prediction of
  missing data are MLP and SVR, and PCA is performed to extract the most important
  data features. Production data with 12 related variables (i.e., dates, hours, temperature,
  pressure, etc.) are used to explore the complex nonlinearity of features and estimate
  wellbore oil production with ML and deep-learning models. Conventional SVR and MLP
  methods are implemented as the benchmark. During this work, more than 60% of the
  missing and abnormal data from the field data set are detected and imputed using
  advanced ML methods, such as MLP and SVR with radial basis function kernel. More
  than 6% of data are outliers and are removed using the z-score method. The modified
  SVR with time-series data structure and long short-term memory (LSTM) algorithms
  are used for the comparisons. An R-squared (R2) of 98% is achieved for both the
  algorithms; however, LSTM has the lowest root mean square error (RMSE) results compared
  to SVR. Data conditioning is conventionally performed using statistical techniques,
  but here, an ensemble of ML techniques is used depending on the available data.
  This paper presents a new methodology to perform data conditioning and production
  prediction for a well pad using ML and neighboring well data. The ML algorithms
  used are highly efficient, as demonstrated by the results.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://doi.org/10.4043/30854-MS
---