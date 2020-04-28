---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ONET Visualization"
summary: ""
authors: []
tags: []
categories: []
date: 2020-04-28T23:33:34+08:00

# Optional external URL for project (replaces project detail page).
external_link: "" # "https://tinyurl.com/jobs-explorer"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
https://tinyurl.com/jobs-explorer

Learning objectives of this personal project is to:
- Learn how to use Dash-Plotly framework for interactive analysis/visualization
- Learn how to use dash-cytoscape package to generate network graphs
- Learn how to deploy on to a cloud provider
- Learn how to use Docker for deployment (in progress)

This is somewhat of an extension of a team project I did for CSE6242. Instead of using our own algorithm to recommend other similar occupations, I am using the recommendations from ONET database. Their methodology which can be found in this [link](https://www.onetcenter.org/reports/Related.html), is definitely more comprehensive than the approach we took - taking into account the manhattan distance between skills composition. Also the data is presented as a network graph to encourage users to visually explore other neighbouring occupations.  

