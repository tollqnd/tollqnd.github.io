---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: Tom J. Holland
header:
  overlay_image: assets/images/splash.jpg
  overlay_filter: linear-gradient(rgba(255, 0, 0, 0.0), rgba(37, 42, 52, 1))
excerpt: 'Musician, Level Designer and Programmer'
feature_row1:
  - image_path: /assets/images/sample.png
    title: "Audio"
    excerpt: "sample"
    url: "/audio"
    btn_label: "Go"
    btn_class: "btn--inverse"
feature_row2:
  - image_path: /assets/images/sample.png
    title: "Level Design"
    excerpt: "sample"
    url: "/level_design"
    btn_label: "Go"
    btn_class: "btn--inverse"
---

{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="right" %}