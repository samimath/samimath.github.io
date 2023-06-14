---
permalink: /test-page/
title: "Sami Furst"
excerpt: "A personal site on learning by doing"
author_profile: true
redirect_from:
  - /test-page/
  - /test-page.html

header:
  overlay_image: ../images/water-blue-ocean.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Jaymantri**](https://www.pexels.com/)"
  actions:
    - label: "More Info"
      url: "https://www.pexels.com"

feature_row:
    #work
  - image_path: ../images/soyfield.jpg
    #image_caption: "Image courtesy of [pexel](https://pexel.com/)"
    alt: "work"
    title: "Work"
    url: "work"
    btn_label: "Read More"
    btn_class: "btn--primary"
    # blog posts    
  - image_path: ../images/macbook.jpg
    alt: "blog"
    title: "Blog"
    url: "year-archive"
    btn_label: "Read More"
    btn_class: "btn--primary"
    # CV
  - image_path: ../images/close-up-of-hand-holding-pencil-over-white-background-316466.jpg
    caption: "Photo credit: [**Lum3n**](https://www.pexels.com)"
    title: "CV"
    url: "cv"
    btn_label: "Read More"
    btn_class: "btn--primary"
    # Cats
  - image_path: ../images/fuzzyface.jpg
    title: "Cats"
    url: "cats"
    btn_label: "Read More"
    btn_class: "btn--primary"      
---

{% include feature_row %}
