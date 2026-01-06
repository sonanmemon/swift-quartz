---
title: 'High Frequency Inflation Forecasting: A Probabilstic Autoregressive Model'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me


date: '2022-07-01T00:00:00Z'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: "I begin by motivating the utility of high-frequency inflation estimation and reviewing recent work done at the State Bank of Pakistan for inflation forecasting and now-casting GDP using machine learning (ML) tools. I also present stylised facts about the structure of historical and especially recent inflation trends in Pakistan. However, since the available data and already used methods cannot achieve high frequency forecasting, I discuss three novel techniques from recent literature, including web scrapping, scanner data and synthetic data. Due to a lack of access to Pakistan’s scanner and web-scrapped data, I generate synthetic data using generative ML models (Gaussian Copula and PAR models) and numerical analysis (cubic spline interpolation) methods. I use cubic splines to estimate the monthly inflation rate from quarterly data and unknown high frequency, weekly inflation rate from actual monthly data. Meanwhile, I use a probabilistic autoregressive ML model to forecast future short-run inflation for Pakistan from 2020 to 2023. I evaluate the accuracy of ML forecasts by comparing them with forecast error variances and predictions from conventional reduced form vector autoregressive models (VAR)."


tags:
  - Time Series Econometrics. High-Frequency Forecasting. Interpolation. 

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: video
    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/clear-hour-glass-on-table-JEKwQbMw7Fo)'
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
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
