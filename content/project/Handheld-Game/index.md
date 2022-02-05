---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Handheld Game"
summary: "Discrete logic & PCB design"
authors: ["lawrence"]
tags: ["complete"]
categories: []
date: 2015-05-01T14:22:43+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

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
After seeing a video on the disassembly of a 1980s child’s game, similar to the popular lane splitter genre of app. I was inspired to recreate my version using technology that was available during that era. By using only discrete logic, this project provided a greater insight into the design process compared to using a microcontroller. Breaking my design down into systems, the gameplay was created using a PRNG and multiple shift registers and a scoring system used a counter and seven segment decoder. The PCB was designed in Kicad and the schematic can be seen here.
