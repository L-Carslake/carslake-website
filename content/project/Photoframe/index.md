---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Digital Photo-frame"
summary: "High resolution display based on the iPad Retina Display and Raspberry PI"
authors: ["Lawrence"]
tags: ["Embedded","complete"]
categories: []
date: 2017-06-23T14:22:23+01:00

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
A market-leading resolution, low-cost digital photo-frame built to fit into any space.

The inspiration for this project was the sourcing a replacement iPad retina display. These displays have a pixel density (230PPI), viewing angle and resolution (2048x1536) significantly better than those used in commercial photo-frame while also having a low cost due to their abundance.

The display was paired with an appropriate driver board for converting the HDMI signal from the Raspberry PI to Embedded Display Port and for creating the required backlight voltages.

The Raspberry PI hosts a custom web interface to control the photos displayed and upload new photos. Both X11 and terminal solutions were investigated for displaying photos with window server implementation chosen for its greater speed when selecting photos.

A traditional photo-frame was modified to provide a case for these components and with an overall style that improves on the crude and cheap housing for other digital photo-frames.
