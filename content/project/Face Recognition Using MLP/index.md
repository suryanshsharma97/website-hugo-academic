---
title: Face Recognition Using MLP
summary: My undergraduate final year group project on the topic of face recognition using Deep Learning.
tags:
  - Deep Learning
date: '2017-11-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Suryansh
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Facial recognition is a method (biometric) of identifying an individual by comparing live capture or a digitally stored image of the individual. It involves three main steps.

1.Analysing features or characteristics.
2.Storing the information in the database.
3.Using the information from database for identification.

It is based on the concept of face print which can be used to quickly and accurately identify an individual under the favourable conditions. These types of systems identify nodal points on a human face. These nodal points are captured from an image source and resulting data is stored as face print which can be further used for performing comparisons to identify an individual.

The above mentioned method is costly in terms of time. Also, the extraction of nodal points (feature extraction) adds to the load of programmer and not to the neural network being used. So, in our project our aim is to use neural network where an image is given as input and it identifies the output class (name of the person).Our objective is to study how the accuracy varies from basic Machine learning models to complex Deep Learning models and whether the transition is effective.