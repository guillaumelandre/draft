---
title: "Home Page"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash2.jpg
  actions:
    - label: "Contactez-nous"
      url: "mailto:hello@infinifemmes.com"
excerpt: "Bacon ipsum dolosssssr sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/pic02.jpg
    alt: "Se retrouver"
    title: "Se retrouver"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/pic04.jpg
    alt: "Proximité"
    title: "Proximité"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/pic06.jpg
    alt: "S'enraciner"
    title: "S'enraciner"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row5:
      - image_path: assets/images/pic03.jpg
        alt: "Approche De Gasquet"
        title: "Approche De Gasquet"
        excerpt: "This is some sample content that goes here with **Markdown** formatting."
      - image_path: /assets/images/pic05.jpg
        alt: "Auto-grandissement"
        title: "Auto-grandissement"
        excerpt: "This is some sample content that goes here with **Markdown** formatting."
        url: "#test-link"
        btn_label: "Read More"
        btn_class: "btn--primary"
      - image_path: /assets/images/pic07.jpg
        alt: "Trikonasana"
        title: "Trikonasana"
        excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row5 %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
