---
title: "The Integrated nested Laplace approximation for fitting models with multivariate response"
authors:
- admin
- Finn Lindgren
- Antonio López-Quílez
- Daniel Simpson
- David Conesa
date: "2020-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""

publication_short: ""

abstract: "This paper introduces a Laplace approximation to Bayesian inference in regression models for multivariate response variables. We focus on Dirichlet regression models, which can be used to analyze a set of variables on a simplex exhibiting skewness and heteroscedasticity, without having to transform the data. These data, which mainly consist of proportions or percentages of disjoint categories, are widely known as compositional data and are common in areas such as ecology, geology, and psychology. We provide both the theoretical foundations and a description of how this Laplace approximation can be implemented in the case of Dirichlet regression. The paper also introduces the package dirinla in the R-language that extends the R-INLA package, which can not deal directly with multivariate likelihoods like the Dirichlet likelihood. Simulation studies are presented to validate the good behaviour of the proposed method, while a real data case-study is used to show how this approach can be applied."


tags:
- Hierarchical Bayesian models
- INLA
- Dirichlet regression
- multivariate likelihood
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/1907.04059
url_code: 'https://bitbucket.org/joaquin-martinez-minaya/dirinla/src/master/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
#slides: example
---


